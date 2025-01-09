# ft_openedugo
Sistema de segumiento de notas  Front end

## Tabla de contenido
1. [Descripción](#descripción)
2. [Requisitos previos](#requisitos-previos)
3. [Instalación](#instalación)
   - [Windows](#windows)
   - [Linux](#linux)
4. [Uso de Docker](#uso-de-docker)
5. [Recursos y documentación](#recursos-y-documentación)

---

## Descripción

**bk_openedugo - Frontend** es la interfaz de usuario desarrollada utilizando **React**, una de las bibliotecas más populares para la creación de aplicaciones web modernas. Este proyecto incluye:

- **React**: Biblioteca principal para el desarrollo de la interfaz.
- **Versionado**: Control de versiones con Git.
- **Docker**: Configuración para ejecutar el frontend en un contenedor Docker.
- **IDE recomendado**: Visual Studio Code.

---

## Requisitos previos

Antes de comenzar, asegúrate de tener instaladas las siguientes herramientas:

- **Node.js**: Versión 18 o superior.
- **npm** o **yarn**: Administradores de paquetes para gestionar las dependencias de React.
- **Docker**: Para ejecutar el contenedor del frontend.
- **Visual Studio Code**: IDE recomendado para el desarrollo.

---

## Instalación

### Windows

1. **Instalar Node.js**:
   - Descarga el instalador desde la [página oficial de Node.js](https://nodejs.org/).
   - Sigue las instrucciones del instalador y verifica la instalación ejecutando:
     ```bash
     node -v
     npm -v
     ```

2. **Instalar Visual Studio Code**:
   - Descarga desde la [página oficial de Visual Studio Code](https://code.visualstudio.com/).
   - Instala extensiones útiles como "ES7+ React/Redux/React-Native snippets" y "Prettier - Code formatter".

3. **Configurar el proyecto React**:
   - Clona el repositorio:
     ```bash
     git clone https://github.com/tuusuario/bk_openedugo-frontend.git
     ```
   - Entra en el directorio y ejecuta:
     ```bash
     cd bk_openedugo-frontend
     npm install
     npm start
     ```

### Linux

1. **Instalar Node.js**:
   - En distribuciones basadas en Debian/Ubuntu:
     ```bash
     sudo apt update
     sudo apt install -y nodejs npm
     ```
   - Verifica la instalación:
     ```bash
     node -v
     npm -v
     ```

2. **Instalar Visual Studio Code**:
   - Descarga desde la [página oficial de Visual Studio Code](https://code.visualstudio.com/Download).
   - Sigue las instrucciones para tu distribución.

3. **Configurar el proyecto React**:
   - Clona el repositorio:
     ```bash
     git clone https://github.com/tuusuario/bk_openedugo-frontend.git
     ```
   - Entra en el directorio y ejecuta:
     ```bash
     cd bk_openedugo-frontend
     npm install
     npm start
     ```

---

## Uso de Docker

Si deseas ejecutar el frontend en un contenedor Docker, sigue estos pasos:

1. **Construir la imagen Docker**:
   - Dentro del directorio del proyecto, ejecuta:
     ```bash
     docker build -t bk_openedugo-frontend .
     ```

2. **Ejecutar el contenedor**:
   - Lanza el contenedor en el puerto 3000:
     ```bash
     docker run -d -p 3000:3000 bk_openedugo-frontend
     ```

3. **Acceder a la aplicación**:
   - Abre tu navegador y ve a `http://localhost:3000`.

---

## Recursos y documentación

- [Documentación oficial de React](https://react.dev/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Docker](https://docs.docker.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Guía de Git](https://git-scm.com/doc)
