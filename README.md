# MEAN_Stack_R
## Aplicación MEAN Stack de Gestión de Productos

Este repositorio contiene una aplicación MEAN Stack que permite a los usuarios gestionar una lista de productos, cumpliendo con las operaciones básicas CRUD (Create, Read, Update, Delete).

## Estructura del Proyecto

El proyecto está dividido en dos carpetas principales:

### Cliente

La carpeta `Cliente` contiene los archivos relacionados con la interfaz de usuario desarrollada con Angular.

- `e2e`: Carpeta de pruebas end-to-end.
- Archivos de configuración para Angular (`angular.json`, `karma.conf.js`, `tsconfig.json`, etc.).
- `src`: Carpeta que contiene los componentes, servicios y otros archivos de la aplicación Angular.

### Servidor

La carpeta `Servidor` contiene el backend de la aplicación utilizando Node.js, Express.js y MongoDB.

- `config`: Archivos de configuración de la aplicación.
- `controllers`: Controladores para manejar las operaciones CRUD.
- `models`: Definición de modelos de datos para interactuar con MongoDB.
- `routes`: Definición de rutas en Express.js.
- Archivos relacionados con Node.js (`index.js`, `package.json`, `variables.env`, etc.).

## Proceso de Integración

1. **Configuración del Proyecto:**
   - Configuración de un nuevo proyecto con MongoDB como base de datos, Express.js como servidor, Angular como cliente y Node.js como entorno de ejecución.

2. **Implementación de Funcionalidades:**
   - Diseño e implementación de rutas en Express.js para realizar operaciones CRUD relacionadas con las tareas.
   - Creación de componentes en Angular para la visualización y manipulación de la lista de tareas.

3. **Pruebas y Verificación:**
   - Realización de pruebas exhaustivas para asegurar el correcto funcionamiento de la aplicación.

## Ejecución de la Aplicación

Para iniciar la aplicación, desde la carpeta `Cliente`, ejecuta el siguiente comando: ``ng serve --o``
