# 🛠️ Proyecto BPMN en Bonitasoft

Bienvenido al repositorio del Proyecto BPMN en Bonitasoft. Aquí encontrarás toda la documentación necesaria sobre el proyecto, sus procesos y su arquitectura. 

## 🏆 Nombre del Equipo y Miembros

- **Equipo de Trabajo:** DSE Qaliwarma Project
  - **Integrantes:**
    - Santiago Vilca Limachi
    - Edson Bryan Béjar Román
    - [Nombre del Integrante 3]
    - [Nombre del Integrante 4]

## 🏢 Cliente: Programa Nacional de Alimentación Escolar Qali Warma.

El nombre de la empresa seleccionada es: Programa Nacional de Alimentación Escolar Qali Warma.

## 🎯 Propósito del Proyecto

El propósito de este proyecto es implementar una solución de **Business Process Management (BPM)** que permita automatizar y gestionar los procesos de negocio de la organización Qaliwarma, mejorando así la eficiencia y la visibilidad de las operaciones.

## 🌟 Visión General

La aplicación BPM incluye:

- **Application Page:** Página principal de la aplicación donde se visualizan y gestionan los procesos.
- **Menú:** Menú de navegación para acceder a las diferentes funcionalidades de la aplicación.

## 📊 Procesos de Negocio

A continuación, se presenta una breve descripción de los procesos de negocio implementados:

- **Proceso 1:** Aprobación del cronograma de convocatoria, bases estandarizadas para el proceso de compras, elaboración y actualización de documentos normativos.

  
- **Proceso 2:** Selección de proveedores.


- **Proceso 3:** Adquisición y distribución de alimentos.


  
- **Proceso 4:** Planificación del menú escolar.


  
- **Proceso 5:** Convocatoria y conducción del proceso de compras según las bases y el manual de aprobados.


  
- **proceso 6:** Gestión de Inventarios locales.


  

## 🏗️ SOA: Servicios de Soporte a Tareas Automáticas

Los servicios de soporte están basados en el estándar **OpenAPI** y utilizan la herramienta **Swagger** para la documentación y prueba de API.

### 📦 Recursos

- **Nombre del Recurso:** <Propósito del Recurso>
  - **Operaciones Disponibles:**
    - **Método:** GET  
      **URLs:** /proj/inventarios/listar  
      **Parámetros:** [Parámetro1, Parámetro2]
    - **Métodos:** POST  
      **URLs:** /proj/inventarios/guardar
      **Parámetros:** [Parámetro1, Parámetro2]

### 🏛️ Modelos

- **Entidades Clave:** Descripción de las entidades clave del sistema.
- **Agregados:** Descripción de los agregados utilizados.
- **Módulos:** Descripción de los módulos clave.

## 🔄 Diagrama de Composición de Servicios
Aquí se detalla el diagrama de composición de servicios a través de los procesos de negocio.
El diagrama está dividido en varias capas, cada una con sus propios módulos y componentes.


![Diagrama de Composición de Servicios](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/d_c_s.png)



### 1. Capa de presentación:
Esta capa se encarga de la interacción con el usuario, proporcionando interfaces y visualizaciones para el funcionamiento del sistema.
  - **Paquete de Proveedores:**
    - La Clase **Empleado** con atributos **id**, **nombre** y **rol**.
      - Rol: Representa al empleado que interactúa con el sistema.
      - Conexión: Interactúa con las capas de gestión de documentos y lógica de negocios.
  - **Paquete de Empleados:**
    - La Clase **Empleado** con atributos **id**, **nombre** y **rol**.
      - Rol: Representa al empleado que interactúa con el sistema.
      - Conexión: Interactúa con las capas de gestión de documentos y lógica de negocios.
  - **Paquete CAE y Padre de Familia:**
    - La Clase **CAE**, **Padre de Familia** con atributos **id**, **nombre** y **telefono**.
      - Rol: Representa usuarios finales que interactúan con el sistema para tomar decisiones decisiones sobre menús escolares.
      - Conexión: Se comunican con la lógica de negocios par definir criterios y elegir menús.

### 2. Capa de Lógica de Negocios:


Esta capa maneja la lógica emresarial del sistema, gestionando las operaciones y procesos de negocio.

  - **Gestión de Proveedores de Servicios:**
    - Clase **GestiónProveedoresServicios** con métodos **listarProveedores**, **agregarProveedor**, **eliminarProveedor**, y **evaluarProveedor**.
      - Rol: Gestiona y evalúa proveedores de servicios.
      - Conexión: Interactúa con las clases **ProveedorDAO**, **EvaluacionDAO**, y **CriteriosDAO** en la capa de acceso a datos.
  - **Evaluación de Proveedores de Servicios:**
    - Clase **EvaluaciónProveedoresServicios** con métodos **historialDesempeño** y **mapProveedor**.
      - Rol: Evalúa el desempeño de los proveedores basándose en criterios definidos.
      - Conexión: Interactúa con **ProveedorDAO** y **EvaluacionDAO**.
  - **Definición de Criterios de Servicio:**
    - Clase **DefiniciónCriteriosServicio** con métodos **agregarCriterio**, **eliminarCriterio**, y **listarCriterios**.
      - Rol: Define y gestiona los criterios de evaluación para los proveedores.
      - Conexión: Se comunica con **CriteriosDAO**.

### 3. Capa de Gestión de Documentos:

Esta capa se encarga de gesteionar la documentación del sistema, incluyendo la creación, revisión, aprobación y publicación de documentos.

  - **Gestión de Documentos:**
    - Clase **GestiónDocumentos** con métodos **crearDocumento**, **eliminarDocumento**, y **editarDocumento**.
      - Rol: Gestiona la creación, edición y eliminación de documentos.
      - Conexión: Interactúa con la clase **RepositorioDocumentos** en la capa de infraestructura.

  - **Revisión Documental:**
    - Clase **RevisiónDocumental** con métodos **iniciarRevisión** y **aprobarRevisión**.
      - Rol: Gestiona el proceso de revisión y aprobación de documentos.
      - Conexión: Se comunica con **RepositorioDocumentos**.

  - **Aprobación Documentaria:**
    - Clase **AprobaciónDocumentaria** con métodos **aprobarDocumento** y **objetarDocumento**.
      - Rol: Gestiona la aprobación final de los documentos.
      - Conexión: Interactúa con **RepositorioDocumentos**.

  - **Publicación:**
    - Clase **Publicación** con métodos **iniciarPublicación** y **finalizarPublicación**.
      -  Rol: Gestiona la publicación de documentos aprobados.
      - Conexión: Se comunica con **RepositorioDocumentos**.
      
### 4. Capa de Acceso a Datos:

Esta capa maneja la persistencia y recuperación de datos del sistema.
  - **ProveedorDAO:**
    - Clase **ProveedorDAO** con métodos **listarProveedores**, **agregarProveedor**, y **eliminarProveedor**.
      - Rol: Accede y manipula datos de los proveedores en la base de datos.
      - Conexión: Interactúa con **GestiónProveedoresServicios**.

  - **EvaluaciónDAO:**
    - Clase **EvaluaciónDAO** con métodos **listarEvaluaciones** y **agregarEvaluación**.
      - Rol: Accede y manipula datos de las evaluaciones en la base de datos.
      - Conexión: Se comunica con **EvaluaciónProveedoresServicios**.

  - **CriteriosDAO:**
    - Clase **CriteriosDAO** con métodos **listarCriterios**, **agregarCriterio**, y **eliminarCriterio**.
      - Rol: Accede y manipula datos de los criterios de evaluación en la base de datos.
      - Conexión: Interactúa con **DefiniciónCriteriosServicio**.

### 5. Capa de Infraestructura:
Esta capa proporciona servicios esenciales y de apoyo al resto del sistema, gestionando los recursos y la infraestructura.
  - **RepositorioDocumentos:**
    - Clase **RepositorioDocumentos** con métodos **guardarDocumento**, **eliminarDocumento**, **actualizarDocumento**, y **obtenerDocumento**.
      - Rol: Gestiona el almacenamiento y recuperación de documentos en el sistema.
      - Conexión: Interactúa con las clases **GestiónDocumentos**, **RevisiónDocumental**, **AprobaciónDocumentaria**, y **Publicación**.
      - 
### 6. Capa de Dominio:
Esta capa maneja la lógica específica de dominio y las reglas de negocio.
  - **Agente Interno:**
    - Clase **AgenteInterno** con atributos **nombre**, **id**, y **responsabilidades**.
      - Rol: Representa a un agente interno del sistema con ciertas responsabilidades.
      - Conexión: Se comunica con la clase **GestiónInventarios**.

  - **Compra:**
    - Clase **Compra** con atributos **id**, **fecha**, **formaDePago**, y métodos **agregarProducto** y **cancelarCompra**.
      - Rol: Gestiona las compras realizadas en el sistema.
      - Conexión: Interactúa con **GestionInventarios**.
     
### 7. Otros Componentes:

- Gestión de Inventarios:
  - Clase **GestionInventarios** con métodos **añadirProducto**, **eliminarProducto**, **actualizarProducto**, **mostrarProducto**.
    - Rol: Gestiona el inventario de productos.
    - Conexión: Interactúa con **AgenteInterno** y **Compra**.

Este diagrama proporciona una estructua clara y organizada para la gestión de proveedores, documentos y servicios dentro de un mismo sistema. Cada capa tiene roles y responsabilidades específicas con clases y también interfaces que aseguran una interacción eficiente y coherente entre los diferentes componentes del sistema. La capa de presentación se encarga de la interacción del usuario, la lógica de negocios maneja las reglas de negocio, la gestión de documentos asegura el flujo adecuado de documentos, el acceso a datos facilita la manipulación de la base de datos y la infraestructura garantiza el almacenamiento seguro y eficiente de los documentos. La capa de dominio representa entidades clave y procesos de negocio que interactúan con las otras capas para cumplir los objetivos del sistema.

## 📄 Documentación Adicional

Para más detalles sobre la implementación, puedes consultar los documentos adicionales en la carpeta `docs`.

---

¡Gracias por visitar el repositorio del Proyecto BPMN en Bonitasoft! Si tienes alguna pregunta o necesitas más información, no dudes en ponerte en contacto con nosotros. 🚀
