# Ecommerce API

## Descripción

API para gestionar un sistema de comercio electrónico, incluyendo funcionalidades para productos...

## Requisitos & Tecnologías

- [Node.js](https://nodejs.org/) (versión 18 o superior)
- [NestJS](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Swagger](https://swagger.io/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [JWT (JSON Web Tokens)](https://jwt.io/)


## Instalación

Pasos para instalar el proyecto.

```bash
# Clonar el repositorio
git clone https://github.com/dev-elliotesco/ecommerce-api.git

# Navegar al directorio del proyecto
cd ecommerce-api

# Instalar dependencias
npm install
```

## Configuración

Antes de ejecutar el proyecto, debes configurar la contraseña de la base de datos Postgres, el nombre de la base de datos y el puerto del servidor de la app como variables de entorno. Crea un archivo `.env` en la raíz del proyecto con el siguiente contenido:

- `DB_PASSWORD` : La contraseña de tu base de datos,  Por ejemplo, `password`.
- `DB_NAME`: El nombre de tu base de datos. Por ejemplo, `ecommerce_db`.
- `APP_PORT`: El puerto en el que se ejecutará el servidor. Por ejemplo, `3000`.


## Ejecución

Pasos para ejecutar el proyecto:

#### Localmente:

```bash
# Inicia el servidor
npm run start:dev
```

#### Docker Compose:

```bash
# Entra en el directorio deployment
cd deployment

# Ejecuta Docker Compose
docker compose --env-file ../.env up -d
```

## Autor
- Elliot Escovicth Riaño - [Github](https://github.com/dev-elliotesco)
- [LinkedIn](https://https://www.linkedin.com/in/elliot-escovitch-580007205/)
- Correo electrónico: eescovitchr@gmail.com

