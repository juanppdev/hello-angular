# Primeros pasos con Angular 18

Este proyecto tiene como objetivo brindar una introducción básica al framework **Angular 18**. Aquí aprenderás los conceptos fundamentales para crear aplicaciones web utilizando Angular y cómo iniciar tu primer proyecto.

## Requisitos previos

Antes de comenzar, asegúrate de tener instalados los siguientes componentes:

- **Node.js** (versión 16.x o superior) - Puedes descargarlo [aquí](https://nodejs.org/)
- **NPM** (Administrador de paquetes de Node.js) - Viene junto con Node.js
- **Angular CLI** - Se instala utilizando npm

## Instalación de Angular CLI

Para poder comenzar a desarrollar con Angular, primero debemos instalar el **Angular CLI** (Command Line Interface). Abre tu terminal y ejecuta el siguiente comando:
npm install -g @angular/cli

Verifica que la instalación haya sido exitosa comprobando la versión instalada:
ng --version

## Crear un nuevo proyecto Angular

Una vez instalado el Angular CLI, puedes generar un nuevo proyecto Angular con el siguiente comando:
ng new nombre-proyecto

Durante el proceso, se te pedirá que respondas algunas preguntas (si deseas agregar routing o el formato CSS a utilizar). Luego, ingresa al directorio de tu proyecto recién creado:
cd nombre-proyecto

## Ejecutar la aplicación

Para iniciar el servidor de desarrollo y ver tu aplicación en el navegador, ejecuta el siguiente comando:
ng serve

Por defecto, tu aplicación estará disponible en http://localhost:4200.


## Estructura del proyecto

Después de generar un proyecto con Angular CLI, la estructura del directorio será la siguiente:
```
├── src
│   ├── app
│   │   ├── app.component.html
│   │   ├── app.component.ts
│   │   └── app.module.ts
│   ├── assets
│   └── environments
├── angular.json
├── package.json
└── tsconfig.json
```

## Descripción de los archivos principales:

 * src/app/app.component.ts: Es el componente principal de la aplicación.
 * app.module.ts: El módulo principal que incluye todos los componentes.
 * angular.json: Archivo de configuración global de la aplicación Angular.

## Conceptos fundamentales

1. Componentes: Los bloques de construcción de Angular. Cada componente tiene una plantilla, un estilo y una lógica asociados.
2. Módulos: Agrupan componentes, servicios y otros elementos que pertenecen a una misma funcionalidad.
3. Directivas: Se usan para manipular el DOM de manera declarativa.
4. Servicios: Se encargan de la lógica empresarial y la interacción con APIs externas.

## Crear un nuevo componente

Para crear un nuevo componente, utiliza el siguiente comando:
ng generate component nombre-componente

Esto generará los archivos relacionados con tu nuevo componente y lo añadirá automáticamente a tu módulo.

## Crear un servicio

Para generar un servicio, usa este comando:
ng generate service nombre-servicio

Un servicio es útil para manejar la lógica de la aplicación y compartir datos entre componentes.

## Recursos adicionales
 * [[Documentación oficial de Angular](https://angular.dev/overview)]
 * [[Tutoriales de Angular](https://angular.dev/tutorials)]

