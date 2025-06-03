# SEM12_PRJ_CRUD_EduardoBullon

Este es un proyecto de **Spring Boot** que implementa una aplicación web con operaciones CRUD para la gestión de la entidad **Alumno**. El proyecto utiliza tecnologías como **JPA** para la persistencia de datos, **AOP** para auditoría y registro de eventos, y **Docker** para la contenedorización y despliegue.

## Tecnologías Utilizadas

- **Spring Boot**: Framework para desarrollar aplicaciones Java de forma rápida y sencilla.
- **JPA (Java Persistence API)**: Para la persistencia de datos en la base de datos.
- **AOP (Aspect-Oriented Programming)**: Para la implementación de funcionalidades transversales como auditoría y logging.
- **Docker**: Para contenedorización de la aplicación y facilitar su despliegue en entornos diferentes.
- **H2 Database**: Base de datos en memoria utilizada para pruebas y desarrollo.
- **Render**: Plataforma utilizada para el despliegue de la aplicación en la nube.

## Descripción

Este proyecto implementa un sistema de gestión de **Alumnos** con operaciones básicas de creación, lectura, actualización y eliminación (CRUD). Además, se incluye la funcionalidad de auditoría utilizando **AOP** y el uso de **JPA** para la interacción con la base de datos. El proyecto está empaquetado y listo para ejecutarse dentro de un contenedor **Docker**, lo que facilita su despliegue y escalabilidad en cualquier entorno compatible.

## Funcionalidades

- **Gestión de Alumnos**: Crear, leer, actualizar y eliminar registros de alumnos en la base de datos.
- **Auditoría con AOP**: Registra automáticamente todas las acciones realizadas en la base de datos.
- **Base de datos en memoria con H2**: Permite visualizar y gestionar datos fácilmente desde la consola.
- **Dockerizado**: Conteneriza la aplicación para facilitar su despliegue.

## Requisitos

- **JDK 17** o superior.
- **Maven**: Para la gestión de dependencias y construcción del proyecto.
- **Docker** (opcional): Si deseas ejecutar la aplicación en un contenedor.

## Instalación

### Clonar el repositorio:

```bash
git clone https://github.com/EduardoBullon/SEM12_PRJ_CRUD_EduardoBullon.git
