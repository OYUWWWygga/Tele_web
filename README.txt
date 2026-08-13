SUBIR A GITHUB

Todos los archivos deben estar juntos en la raíz:
index.html
catalog.html
styles.css
app.js
catalog.json

GitHub Pages: Settings > Pages > Deploy from branch > main > /(root).

IMPORTANTE: catalog.json debe tener exactamente esta estructura: {"movies": [...]} y nunca necesita "version".
La aplicación usa video_url primero; si está vacío, usa trailer_embed_url y después trailer_url.
