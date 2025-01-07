# Prueba Práctica - Jefe de Sistemas en SECOMEXT

Este repositorio contiene una solución para la prueba práctica para la vacante de Jefe de Sistemas en SECOMEXT. La solución está compuesta por una aplicación web desarrollada con Angular (Frontend) y Spring Boot (Backend) para gestionar productos y categorías.

## Descripción del Proyecto

El sistema permite gestionar productos y categorías con las siguientes funcionalidades:

### Funcionalidades

- **Frontend (Angular)**:
  - Listado de productos con nombre, precio y categoría.
  - Formulario para crear y editar productos.
  - Listado de categorías.
  - Validación de formularios.
  - Interfaz de usuario utilizando Angular Material.

- **Backend (Spring Boot)**:
  - Endpoints REST para gestionar productos y categorías:
    - Crear, listar, actualizar y eliminar productos.
    - Crear, listar, actualizar y eliminar categorías.
  - Base de datos en memoria (H2).
  - Autenticación y autorización con Spring Security.
  - Documentación del API utilizando Swagger.

## Instrucciones para ejecutar el proyecto

### Backend (Spring Boot)

1. Clona este repositorio.
2. Entra en el directorio `backend` y ejecuta el siguiente comando para levantar el servidor:
   ```bash
   mvn spring-boot:run

