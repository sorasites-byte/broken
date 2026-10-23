# brokerandreahriosa — sitio listo para publicar

Esta carpeta es el sitio completo, ya compilado. No necesita instalar nada.

- **Ver en el ordenador:** abre `index.html` con doble clic.
- **Publicar en GitHub Pages:**
  1. Crea un repositorio en GitHub y sube TODO el contenido de esta carpeta
     (Add file → Upload files → arrastra los archivos y carpetas → Commit).
  2. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
  3. En 1–2 minutos el sitio estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

Contenido:
- `index.html` — la página.
- `assets/` — código (`app.js`, `style.css`), tipografías (`assets/fonts`), imágenes (`assets/images`) y
  fotogramas de la animación de entrada (`assets/intro`).
- `favicon.svg`, `robots.txt`, `.nojekyll`.

Para cambiar textos, datos o imágenes edita el código fuente (proyecto React) y vuelve a
generar esta carpeta con `npm run build`.
