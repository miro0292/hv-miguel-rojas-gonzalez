# CV de Miguel Rojas González

Portafolio/CV en HTML/CSS/JS con tema neutral y moderno. Incluye:
- `index.html` (interactivo, con barras de habilidades)
- `assets/profile.json` (fuente de datos)
- `CV_Miguel_Rojas_Gonzalez.pdf` (versión PDF extendida, 2 páginas)

## Cómo publicar en GitHub Pages
1. Crear un repo nuevo (p.ej. `cv-miguel`).
2. Subir la carpeta completa de `cv_miguel` al repo (el contenido, no la carpeta padre).
3. En **Settings → Pages**, seleccionar **Deploy from Branch** y elegir la rama principal y `/root`.
4. La página quedará disponible en `https://<usuario>.github.io/<repo>/`.

## Editar contenidos
- Cambiar textos y porcentajes en `assets/profile.json`.
- El botón **Descargar PDF** apunta a `../CV_Miguel_Rojas_Gonzalez.pdf` (un nivel arriba). Si hospedás todo en la raíz del repo, dejá ambos archivos (HTML y PDF) en la raíz y actualizá el `href` a `./CV_Miguel_Rojas_Gonzalez.pdf`.
