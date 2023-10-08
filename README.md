# Proyecto SQLite con JavaScript, Sequelize y Express

Este proyecto es una aplicación CRUD (Create, Read, Update, Delete) básica que utiliza SQLite como base de datos, JavaScript como lenguaje de programación, Sequelize como ORM (Object-Relational Mapping) y Express como framework de servidor.

## Características

- Creación, lectura, actualización y eliminación de usuarios y tareas.
- Uso de SQLite como base de datos relacional.
- Uso de Sequelize para interactuar con la base de datos SQLite.
- Uso de Express para manejar las solicitudes y respuestas del servidor.

## Estructura del Proyecto

El proyecto se divide en varias partes:

- `src/db.js`: Este archivo configura y establece la conexión con la base de datos utilizando Sequelize.
- `src/models/`: Este directorio contiene los modelos Sequelize para las tablas de la base de datos.
- `src/routes/`: Este directorio contiene las rutas Express para manejar las solicitudes HTTP a diferentes endpoints.
- `src/libs/config.js`: Este archivo contiene la configuración de la base de datos.
- `src/libs/boot.js`: Este archivo inicia el servidor Express.
- `src/index.js`: Este es el punto de entrada de la aplicación.

## Cómo ejecutar el proyecto

1. Clona el repositorio en tu máquina local.
2. Navega hasta el directorio del proyecto en tu terminal.
3. Ejecuta `npm install` para instalar las dependencias del proyecto.
4. Ejecuta `npm run dev` para iniciar el servidor en modo de desarrollo.

## Tecnologías utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Sequelize](https://sequelize.org/)
- [SQLite](https://www.sqlite.org/index.html)
