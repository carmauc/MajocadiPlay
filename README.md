<<<<<<< HEAD
# MAJOCADIPLAY: Visualización de Películas y Series

![Icono de la aplicación](./FRONT/public/logo.png)

Este proyecto es una aplicación web para la visualización de información de películas y series. Utiliza tecnologías modernas tanto en el frontend como en el backend para ofrecer una experiencia fluida y segura para los usuarios.

## Tecnologías Utilizadas
**Frontend:**

- **React**: Biblioteca JavaScript para construir interfaces de usuario interactivas.
- **React Router DOM**: Para manejar la navegación y las rutas en la aplicación.

**Backend:**

- **Java**: Lenguaje de programación utilizado para el back-end.
- **Spring Boot**: Framework para crear aplicaciones Java de manera rápida y sencilla.
- **Hibernate**: Biblioteca para mapear objetos Java a tablas de base de datos.

**Base de Datos:**
  - MySQL alojada en AWS Amazon


## Características Principales

- **Protección de Rutas:**:
La aplicación maneja rutas públicas y privadas. Algunas páginas solo son accesibles para usuarios autenticados.
Se utiliza React Router DOM para gestionar las rutas.

- **Autenticación Y Validación:**
Los usuarios pueden registrarse e iniciar sesión.
La validación de usuario y contraseña se realiza directamente en la base de datos.

- **Gestión de Películas por Administradores:** Los usuarios administradores tienen la capacidad de crear, borrar o actualizar la información de las películas directamente en la base de datos, lo que permite una gestión completa y directa de los contenidos.

