## Tía Vicenta

Este proyecto es una aplicación web desarrollada en Angular 13 que permite a los usuarios ver y compartir recetas de cocina. Está alojado en Firebase Hosting.

### Tecnologías utilizadas
- Angular: framework de desarrollo web.
- Firebase: plataforma de desarrollo de aplicaciones móviles y web.
- Tailwind CSS: framework de CSS.
- Jasmine: framework de pruebas unitarias para JavaScript.
- Karma: test runner para pruebas unitarias de JavaScript.
- Protractor: framework de pruebas e2e para aplicaciones Angular.
- Cypress: framework de pruebas e2e para aplicaciones web.
## Configuración

### Requisitos previos

Para ejecutar este proyecto, debes tener instalado:

- Node.js
- npm

### Instalación

1. Clona el repositorio en tu equipo local.
2. Navega a la carpeta del proyecto y ejecuta `npm install` para instalar todas las dependencias.
3. Ejecuta `npm start` para iniciar la aplicación. La aplicación se abrirá en tu navegador por defecto en `http://localhost:4200/`.

### Ejecución de pruebas

- Para ejecutar las pruebas unitarias, usa el comando `npm run test`.
- Para ejecutar las pruebas e2e con Protractor, usa el comando `npm run e2e`.
- Para ejecutar las pruebas e2e con Cypress, usa el comando `npm run cypress`.

Implementación
-----------------

El proyecto está configurado para implementarse en Firebase Hosting. Para implementar la aplicación, sigue los siguientes pasos:

1. Crea una cuenta en Firebase y crea un proyecto.
2. Configura tu proyecto de Firebase para que funcione con esta aplicación de Angular. Sigue las instrucciones de la documentación oficial de Firebase.
3. Ejecuta el comando `npm run build --prod` para crear una versión optimizada para producción de la aplicación.
4. Ejecuta el comando `firebase login` e inicia sesión con tu cuenta de Firebase.
5. Ejecuta el comando `firebase init hosting`. Sigue las instrucciones para configurar Firebase Hosting.
6. Ejecuta el comando `firebase deploy` para implementar la aplicación en Firebase Hosting.
