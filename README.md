# 🎤 Festival de Música 🎉

¡Bienvenido al proyecto del Festival de Música! Este sitio web te permitirá organizar y disfrutar de un increíble festival de música, con secciones de información general, lineups y opciones de boletos.

## 📋 Requisitos

Para preparar tu entorno de desarrollo, asegúrate de tener instalados **Node.js** y **Gulp**.

## 🚀 Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/usuario/repo.git
    ```
2. Instala las dependencias necesarias:
    ```bash
    npm install
    ```

## 🏗️ Estructura del Proyecto

- `src/` - Archivos fuente, incluidos HTML, SCSS y JavaScript.
- `build/` - Archivos generados y optimizados para producción.
- `gulpfile.js` - Tareas de Gulp para automatizar el proceso de construcción.
- `package.json` - Dependencias y scripts del proyecto.

## 📋 Tareas de Gulp

- **🎨 css:** Compilación de SCSS a CSS, almacenado en `build/css`.
- **📷 imagenes:** Optimización de imágenes PNG y JPG, guardadas en `build/img`.
- **🌐 versionWebp:** Conversión de imágenes a formato WebP, guardadas en `build/img`.
- **🖼️ versionAvif:** Conversión de imágenes a formato AVIF, guardadas en `build/img`.
- **🚀 javascript:** Minificación y optimización de JavaScript, guardado en `build/js`.
- **🔄 dev:** Ejecuta tareas en paralelo y observa cambios para recompilación automática.

## 🛠️ Uso

Para compilar SCSS, optimizar imágenes y minificar JavaScript, usa:
```bash
gulp dev
```

## 🔧 Tecnologías utilizadas

- **Gulp**
- **SCSS**
- **JavaScript**
