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

- **Proceso 1:** Gestion de Inventarios.
- **Proceso 2:** Descripción breve del proceso.
- **Proceso 3:** Descripción breve del proceso.

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
![Diagrama de Composición de Servicios]([ruta/al/diagrama.png](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/d_c_s.png)
**1. Capa de presentación:**
Esta capa se encarga de la interacción con el usuario, proporcionando interfaces y visualizaciones para el funcionamiento del sistema.
  - **Paquete de Proveedores:**
    - La Clase **Empleado** con atributos **id**, **nombre** y **rol**.
    - Rol: representa al empleado que interactúa con el sistema.
    - Conexión: Interactúa con las capas de gestión de documentos y lógica de negocios.
  - **Paquete de Empleados:**
    - La Clase **Empleado** con atributos **id**, **nombre** y **rol**.
    - Rol: Representa al empleado que interactúa con el sistema.
    - Conexión: Interactúa con las capas de gestión de documentos y lógica de negocios.
  - **Paquete CAE y Padre de Familia:**
    - La Clase **CAE**, **Padre de Familia** con atributos **id**, **nombre** y **teléfono**.
    - Rol: Representa usuarios finales que interactúan con el sistema para tomar decisiones decisiones sobre menús escolares.
    - Conexión: Se comunican con la lógica de negocios par definir criterios y elegir menús.



   

## 📄 Documentación Adicional

Para más detalles sobre la implementación, puedes consultar los documentos adicionales en la carpeta `docs`.

---

¡Gracias por visitar el repositorio del Proyecto BPMN en Bonitasoft! Si tienes alguna pregunta o necesitas más información, no dudes en ponerte en contacto con nosotros. 🚀
