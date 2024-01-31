# Auth APP

El actual proyecto dispone de los componentes necesarios para registrar y autenticar usuarios de manera rápida y eficiente. La lógica de autenticación y registro implementada es sencilla, lo que te permitirá ajustar fácilmente la funcionalidad para adaptarla a las necesidades específicas de tu proyecto, en caso de requerir validaciones adicionales o más complejas.

El proyecto puede ejecutarse sin problemas; sin embargo, es de suma importancia contar con un backend capaz de recibir las solicitudes HTTP generadas desde el frontend. Por esta razón, recomiendo clonar el proyecto [Auth Laravel API](https://github.com/JoanArturo/auth-laravel-api). Este proyecto está desarrollado con Laravel 10 y cuenta con los endpoints necesarios para garantizar un funcionamiento adecuado con el proyecto actual de Angular.

## Pre-requisitos 📋

Para la correcta ejecución de este proyecto, necesitas tener las siguientes tecnologías instaladas en tu ordenador.
* npm 9.6.7
* Angular CLI 16.2.11

**IMPORTANTE: Es indispensable tener clonado y en ejecución el proyecto [Auth Laravel API](https://github.com/JoanArturo/auth-laravel-api)**

## Instalación 🔧

1. Clona este proyecto.
```bash
git clone https://github.com/JoanArturo/auth-app.git
```

2. Instala las dependencias de node con npm.
```bash
npm install
```

3. Ejecuta el proyecto Angular en modo desarrollo y navega a `http://localhost:4200/`.
```bash
ng serve
```

4. Ejecuta el proyecto backend `Auth Laravel API` realizado con Laravel para que la aplicación Angular consuma los endpoints, si aún no lo tienes puedes clonarlo desde el [repositorio Auth Laravel API](https://github.com/JoanArturo/auth-laravel-api).

## Construido con 🛠️

- [npm 9.6.7](https://www.npmjs.com/package/npm/v/9.6.7)
- [Angular CLI 16.2.11](https://angular.io/docs)
- [Bootstrap 5.3.2](https://getbootstrap.com/)

## Autor 🖋️

- [@JoanArturo](https://github.com/JoanArturo)
