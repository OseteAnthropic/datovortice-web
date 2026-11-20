# DatoVortice — sitio web

Sitio estático (HTML + CSS, sin JavaScript, sin cookies ni recursos externos) de **DatoVortice**, canal de YouTube de historia, geografía y curiosidades: <https://www.youtube.com/@DatoVortice>.

Presenta el canal y explica su herramienta privada de automatización (uso propio, API de YouTube Data v3). Incluye la política de privacidad y las condiciones del servicio.

## Estructura

- `index.html` — portada
- `privacidad.html` — política de privacidad
- `condiciones.html` — condiciones del servicio
- `styles.css` — estilos
- `assets/` — logotipo y emblema del canal
- `favicon.ico`
- `.nojekyll` — GitHub Pages sirve los archivos tal cual

Todas las rutas son relativas, por lo que funciona dentro de `/datovortice-web/`.

## Ver en local

Abre `index.html` en el navegador, o desde esta carpeta: `python -m http.server 8080` y visita <http://localhost:8080/>.

## Contenido del repositorio

Solo archivos públicos. Este repositorio **no** contiene credenciales, claves, tokens, código de automatización, vídeos ni narraciones.
