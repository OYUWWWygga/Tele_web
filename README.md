# TO2PELISFOCUS — versión mejorada

## Incluye
- `index.html`: catálogo principal.
- `intro.html`: pantalla inicial corregida; redirige a `index.html`.
- `player.html`: reproductor independiente opcional.
- `catalog.json`: esquema versionado listo para rellenar.
- `css/styles.css` y `js/app.js`: estilos y lógica separados.

## Publicación en GitHub Pages
1. Sube todos los archivos conservando las carpetas `css` y `js`.
2. Configura GitHub Pages para publicar desde la rama principal.
3. Usa `intro.html` como portada o renómbralo a `index.html` y cambia el nombre del catálogo actual.
4. Mantén `catalog.json` en la misma carpeta que `index.html`.

## Formato de entrada
```json
{
  "title": "Título",
  "type": "Terror",
  "year": 2026,
  "description": "Descripción",
  "poster_url": "https://...",
  "is_featured": true,
  "video_url": "https://...",
  "trailer_url": "https://...",
  "tmdbid": 123
}
```

`video_url` se usa primero. Si está vacío, se usa `trailer_url`. Utiliza solo contenido y enlaces que tengas autorización para publicar o insertar.
