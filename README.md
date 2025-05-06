# 📦 Proyecto: Autenticación y Conexión con APIs

Este proyecto es un ejemplo práctico que muestra cómo manejar la autenticación de usuarios, realizar conexiones a bases de datos simuladas y consumir APIs externas utilizando JavaScript moderno. También muestra cómo interactuar con el almacenamiento local del navegador (localStorage).

## 🧩 Estructura de Archivos

El proyecto tiene dos archivos principales:

- **`autenticar.js`**: Este archivo contiene una función para manejar la autenticación de usuarios y una constante que almacena el número de "likes".
- **`storage-modules.js`**: Este archivo maneja la simulación de una conexión a una base de datos externa, consume una API de productos y otra de usuarios, y guarda los datos obtenidos en el almacenamiento local del navegador.

## 🔧 Tecnologías Utilizadas

- **JavaScript (ESModules)**: Utiliza la sintaxis moderna de módulos para organizar el código.
- **Promesas y async/await**: Permite manejar operaciones asincrónicas de manera eficiente.
- **Fetch API**: Utiliza esta API para hacer solicitudes HTTP a servicios externos.
- **localStorage**: Permite almacenar datos en el navegador de manera persistente.
- **Fake Store API y JSONPlaceholder API**: APIs de ejemplo para simular datos de productos y usuarios.

## 🚀 Funcionalidades

### Autenticación de Usuarios
El proyecto tiene una función para simular el proceso de autenticación de un usuario. Cuando el usuario ingresa su nombre de usuario, se muestra un mensaje de bienvenida en la consola.

### Simulación de Conexión a Base de Datos
El proyecto simula una conexión a una base de datos externa utilizando promesas. Esta conexión se resuelve exitosamente o se rechaza dependiendo de la simulación.

### Consumo de APIs Externas
El proyecto consume la Fake Store API para obtener productos y mostrar información de productos como el nombre y el precio. También se conecta a la JSONPlaceholder API para obtener datos de usuario (como el nombre y el correo electrónico), que luego se guarda en el almacenamiento local del navegador (localStorage).

## ▶️ Ejecución del Proyecto

### ✅ Requisitos

Para ejecutar este proyecto, necesitarás:

- Un navegador moderno que soporte módulos ES.
- Un servidor local (puedes usar Live Server en Visual Studio Code o cualquier servidor que soporte JavaScript moderno).

### 🧪 Cómo probar

1. Clona este repositorio en tu máquina local.
2. Abre el archivo `storage-modules.js` en tu entorno local.
3. Abre la consola del navegador para ver los resultados de las operaciones, como la autenticación del usuario, la simulación de la conexión a la base de datos y la obtención de productos y usuarios desde las APIs.


Abre el archivo storage-modules.js en tu entorno local.

Abre la consola del navegador para ver los resultados de las operaciones, como la autenticación del usuario, la simulación de la conexión a la base de datos y la obtención de productos y usuarios desde las APIs.
