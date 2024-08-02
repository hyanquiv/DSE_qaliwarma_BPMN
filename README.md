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

- ### Proceso 1:
Aprobación del cronograma de convocatoria, bases estandarizadas para el proceso de compras, elaboración y actualización de documentos normativos.
  
![Diagrama del proceso](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/proceso_actualizar_documentos_normativos_manual_operaciones.PNG)
**Descripción del proceso:**

Este proceso garantiza una revisión exhaustiva y cumplimiento normativo del Manual de Operaciones antes de su implementación. La Unidad de Planeamiento prepara y envía el manual para revisión. La Dirección Ejecutiva y la Asesoría Jurídica revisan el manual para asegurar su precisión y cumplimiento legal. Finalmente, MIDIS aprueba el manual y la Coordinación General de Gestión de Contratos lo implementa. Este flujo estructurado asegura que el manual esté completamente validado y listo para su aplicación efectiva.

**FASE 1: Planificación**
  - **1.1 Unidad de Planeamiento, Presupuesto y Modernización**
    - **1.1.1 Planificar el Manual de Operaciones**
      -Prepara una versión preliminar del manual.
    - **1.1.2 Mandar el Manual de Operaciones para Revisión**
      -Envía el manual preliminar a la **Dirección Ejecutiva** para su revisión.

**FASE 2: Revisión del Manual de Operaciones**
  - **2.1 Dirección Ejecutiva**
     - **2.1.1 Recibir el Manual de Operaciones**
       - Recepción del manual enviado por la **Unidad de Planeamiento**.
     - **2.1.2 Revisar el Manual de Operaciones**
       - Verifica el contenido del manual. Si requiere cambios, se reenvía para corrección.
  - **2.2 Asesoría Jurídica**
    - **2.2.1. Verificar que el Manual de Operaciones corresponde legalmente**
       - Asegura el cumplimiento legal del manual. Si es correcto, notificar a la **Dirección Ejecutiva**.
  - **3.3 MIDIS**
    - **3.3.1 Recibir el Manual de Operaciones**
      - Recepción del manual aprobado por la **Dirección Ejecutiva**.
    - **3.3.2 Revisión del Manual de Operaciones**
      - Realiza una revisión final. Si requiere cambios, notificar y reenviar para corrección.

**FASE 3: Ejecución del Manual de Operaciones**
  - **3.1 Coordinación General de Gestión de Contratos de Servicios Alimentarios**
    - **3.1.1 Oficializar la Aprobación del Manual de Operaciones**
       - Comunica la aprobación del manual a todas las partes interesadas.
    - **3.1.2 Comenzar la Ejecución del Programa Alimentario siguiendo el Manual de Operaciones Aprobado**
       - Inicia la ejecución del programa conforme a las directrices del manual aprobado.



  
- ### Proceso 2: Selección de proveedores.
  
![Diagrama de proceso de selección de proveedores](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/proceso_seleccion_proveedores.png)

**Descripción del proceso:**

Este diagrama describe el proceso de selección de proveedores. El flujo comienza con la recopilación de información sobre los proveedores potenciales, luego, se definen los criterios de selección que serán usados para evaluar los proveedores.
El proceso inluye una evaluación inicial para determinar si los proveedores cumplen con los requisitos establecidos. Si los cumplen, se realizan una evaluación más detallada, seguida de ajustes y la aprobación de la solicitud. So no cumplen, se notifica el rechazo y el proceso termina.
Generalmente, el proceso asegura que solo los proveedores que cumplen con los criterios predefinidos avanzan en el proceso de selección.




- ### Proceso 3: Adquisición y distribución de alimentos.

![Diagrama de proceso de adquisición y distribución de alimentos](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/proceso_adquisicion_alimentos.png)
**Descripción del proceso:**
Este proceso asegura una planificación buena y eficiente, la organización de los pedidos, y una correcta distribución y recepción de alimentos en las unidades territoriales.

**Etapas del proceso:**

**1. Planificación y Presupuesto:**

  - **1.1 Recepción de Alimentos:**
    - El proceso comienza con la recepción de una lista de alimentos.
  - **1.2 Generación de Presupuesto:**
    - Se genera un presupuesto basado en la lista de alimentos.
  - **1.3 Evaluación de Financiamiento:**
    - Se realiza una evaluación para determinar si los alimentos pueden financiarse.
      - **1.3.1** Si no es posible, se ajusta el informe.
      - **1.3.2** Si es posible, se envía el informe final.

**2. Generación y Organización de Pedidos:**

  - **2.1 Recepción del Informe Final:**
    - El informe final es recibido por la unidad de gestión.
  - **2.2 Organización de Comités de Compra:**
    - Se organizan comités de compra para dividir los pedidos entre proveedores.
  - **2.3 Generación y Envío de Pedidos:**
    - Tras la división, se generan y envían los pedidos a los proveedores.

**3. Logística y Distribución:**

  - **3.1 Organización de Pedidos:**
    - Los pedidos recibidos se organizan por unidades territoriales.
  - **3.2 Generación de Rutas de Entrega:**
    - Se generan las rutas de entrega.
  - **3.3 Notificación de Entrega:**
    - Se notifica a las unidades sobre los días de entrega.

**4. Recepción y Supervisión:**

  - **4.1 Recepción de Pedidos en Unidades Territoriales:**
    - En las unidades territoriales, se reciben y revisan los pedidos.
  - **4.2 Supervisión de Entregas:**
    - Finalmente, se supervisa la entrega adecuada y se notifica el recibimiento de los productos.



  
- ### Proceso 4: Planificación del menú escolar.
  
![Diagrama de proceso de planificaión del menú escolar](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/proceso_menu_escolar.png)

**Descripción del proceso:**

El proceso garantiza que el menú escolar sea cuidadosamente planificado, cumpla con los estándares nutricionales y se ajuste a las necesidades y preferencias de estudiantes antes de ser aprobado y enviado para su implementación.

La participación de los padres y el comité escolar en la retroalimentación asegura un enfoque inclusivo y orientado a esa comunidad.

**Etapas del proceso:**

  - **1. Recepción y Recopilación de Datos**
    - **1.1 Recepción de Productos:** 
      - El proceso comienza con la recepción de productos, lo que indica la disponibilidad de ingredientes para la planificación del menú.
    - **1.2 Recopilación de Preferencias y Necesidades:** 
      - Se recopilan datos sobre las preferencias y necesidades alimenticias de los estudiantes, lo que puede incluir alergias, restricciones dietéticas, y preferencias culturales.

  - **2. Análisis y Formulación del Menú**

    - **2.1 Análisis de Datos:** 
      - Se analizan los datos recopilados para asegurar que se ajusten a los requisitos nutricionales y a las necesidades de los estudiantes.
    - **2.2 Cumple Estándar Nutricional:** 
      - Se realiza una verificación para determinar si el menú propuesto cumple con los estándares nutricionales. 
      - Si no cumple, se reformula el menú.
    - **2.3 Reformulación:** 
      - Si es necesario, se realizan ajustes al menú para cumplir con los estándares nutricionales.

  - **3. Presentación y Aprobación del Menú**
    - **3.1 Presentación del Menú:** 
      - Una vez que el menú cumple con los estándares, se presenta a las partes interesadas, que en este caso pueden ser los padres de familia o el comité escolar.
    - **3.2 Encuesta:** 
      - Se puede llevar a cabo una encuesta para recoger opiniones o sugerencias sobre el menú propuesto.

  - **4. Aprobación del Menú**

    - **4.1 Aprobar Menú:** 
      - Se decide si el menú es aprobado o no. 
        - Si es aprobado, el proceso avanza.
        - Si no es aprobado, se proporciona retroalimentación y se realizan los ajustes necesarios.
    - **4.2 Retroalimentar:** 
      - En caso de que el menú no sea aprobado, se devuelve con comentarios para su revisión y ajustes.
    - **4.3 Añadir a las Opciones del Menú:** 
      - Una vez que se cumplen todos los criterios, el menú es añadido a las opciones disponibles.

  - **5. Notificación y Envío del Menú**
    - **5.1 Notificar Aprobación:** 
      - Se notifica la aprobación del menú a las entidades responsables.
    - **5.2 Menú enviado al ente ejecutor:** 
      - Finalmente, el menú aprobado se envía a la entidad encargada de su ejecución.


  
- ### Proceso 5: Convocatoria y conducción del proceso de compras según las bases y el manual de aprobados.
  
![Diagrama de proceso de compras](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/proceso_compras.png)

  
- ### proceso 6: Gestión de Inventarios locales.
  
![Diagrama de proceso de gestión de inventarios](https://github.com/hyanquiv/DSE_qaliwarma_BPMN/blob/proceso_compras/files/proceso_gestion_inventarios.PNG)

  

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
