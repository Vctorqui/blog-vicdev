
![blog-logo](https://github.com/user-attachments/assets/abe6f530-723e-4d4d-8924-2b6d40cd58c8)
# Share It Blog 🚀

Bienvenido a **Share It**. Un rincón para compartir los conocimientos y recursos que me han guiado y ayudado, tanto a mí como a otros desarrolladores, en nuestro recorrido. 🌟

## Funcionalidades

- 📝 Publicación de artículos
- 🏷️ Categorías y etiquetas para organizar el contenido
- 🔍 Búsqueda de artículos

## Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/blog-vicdev.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd blog-vicdev
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Inicia el servidor de desarrollo:

   ```bash
   npm start
   ```

5. Abre tu navegador y ve a `http://localhost:4321` para ver el blog en funcionamiento. 🌐

## Contribuir

¡Las contribuciones son bienvenidas! 🎉 Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu funcionalidad o corrección de errores:

   ```bash
   git checkout -b nombre-de-tu-rama
   ```

3. Realiza tus cambios y haz commit:

   ```bash
   git commit -m "Descripción de tus cambios"
   ```

4. Sube tus cambios a tu repositorio fork:

   ```bash
   git push origin nombre-de-tu-rama
   ```

5. Abre un Pull Request en GitHub y describe los cambios que has realizado.

## Añadir Artículos y Recursos

Para añadir nuevos artículos y recursos al blog, sigue estos pasos:

1. Crea un nuevo archivo Markdown en el directorio `src/content/articles/` o `src/content/resources` con la siguiente estructura:

   ```typescript
   ---
   title: 'Título del Artículo'
   date: 'YYYY-MM-DD'
   author: 'Nombre del Autor'
   tags: 'etiqueta'
   ---
   Contenido del artículo en formato Markdown.

   ```

2. Guarda el archivo y el nuevo artículo aparecerá automáticamente en el blog. ✨

## Añadir Colaboradores

Para aparecer en la sección de colaboradores, añade tus datos dentro de los archivos Markdown de artículos o recursos (`src/content/articles/` o `src/content/resources`). Asegúrate de incluir la información del autor en el siguiente formato:

```markdown
---
author:
  name: 'Nombre del Autor'
  avatar: 'URL del Avatar'
  role: 'Rol del Autor'
  github: 'URL de GitHub'
  linkedin: 'URL de LinkedIn'
---
```

¡Gracias por visitar Share it! 🙌

## Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
