# 🛠️ Proyecto BPMN en Bonitasoft

Bienvenido al repositorio del Proyecto BPMN en Bonitasoft. Aquí encontrarás toda la documentación necesaria sobre el proyecto, sus procesos y su arquitectura. 

## 🏆 Nombre del Equipo y Miembros

- **Equipo de Trabajo:** DSE Qaliwarma Project
  - **Integrantes:**
    - Santiago Vilca Limachi
    - [Nombre del Integrante 2]
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

## 🏗️ SOLID: Aplicación de los prinicipios

Aquí explicamos cómo aplicamos los principios SOLID en nuestro proyecto

### 🏛️ Single Responsibility Principle (Principio de responsabilidad única)

Este principio se aplica en la definición de clases y métodos, aquí se puede ver la clase InventarioEntity donde se definen métodos para obtener y cambiar las variables necesarias sin interferir con otros dependencias, cada método se encarga solo de su funcionalidad

![Principio de Responsabilidad Única](images/S_Principle.png)

### 🏛️ Open-Closed Principle (Principio Abierto-Cerrado)
### 🏛️ Liskov Substitution Principle (Principio de responsabilidad única)
### 🏛️ Interface Segregation Principle (Principio de segregación de interfaz)
### 🏛️ Dependency Inversion Principle (Principio de inversión de dependencia)

## 🔄 Diagrama de Composición de Servicios

Aquí se detalla el diagrama de composición de servicios a través de los procesos de negocio:

![Diagrama de Composición de Servicios](ruta/al/diagrama.png)

## 📄 Documentación Adicional

Para más detalles sobre la implementación, puedes consultar los documentos adicionales en la carpeta `docs`.

---

¡Gracias por visitar el repositorio del Proyecto BPMN en Bonitasoft! Si tienes alguna pregunta o necesitas más información, no dudes en ponerte en contacto con nosotros. 🚀
