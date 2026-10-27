# Portfolio — Gracia Enríquez

Sitio estático para GitHub Pages: https://graenr-design.github.io/porfolio/

## Estructura
- `index.html` — home
- `aristocrazy/`, `suarez/`, `patek-philippe/`, `correos-prepago/` — casos de estudio
- `cv/` — CV (página A4 imprimible; Ctrl/Cmd+P para guardar en PDF)
- `assets/` — imágenes
- `support.js` — runtime de las páginas (necesario)
- `og-image.png`, `favicon.png`, `apple-touch-icon.png` — miniatura y favicons
- `robots.txt`, `sitemap.xml`, `404.html`, `.nojekyll`

## Publicar
1. Sube **el contenido** de esta carpeta a la raíz del repo `graenr-design/porfolio` (rama `main`).
2. GitHub → Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. Espera 1–2 min y abre https://graenr-design.github.io/porfolio/

Si cambias el nombre del repo o usas dominio propio, actualiza la URL base en las etiquetas `canonical`/`og:*` de cada `index.html`, en `sitemap.xml`, `robots.txt` y `404.html`.
