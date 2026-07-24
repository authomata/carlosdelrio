# Carlos del Río — sitio web

Sitio estático de una sola página. Sin build, sin dependencias.

## Estructura
```
index.html            la página completa (estilos inline en <head>)
assets/
  carlos-del-rio.webp   foto del hero
  carlos-contemplacion.webp  banda fotográfica
  rostros-del-infinito.webp  portada del libro
  albums/               9 carátulas (600×600 webp)
favicon.svg
vercel.json           cabeceras de caché
```

## Desarrollo local
Abrí `index.html` en el navegador, o servilo:
```
npx serve .
```

## Deploy en Vercel
Importá el repo en Vercel. Framework Preset: **Other**. Sin build command, output directory: `.`

## Pendientes
- **Formulario de sesiones:** hoy solo muestra confirmación en pantalla, no envía nada. Conectar a Formspree, a una Vercel Function o al servicio de email que use Carlos (ver el `<script>` al final de `index.html`).
- **Enlace de compra del libro:** apunta al WordPress antiguo (`wordpress-1088143-4675072.cloudwaysapps.com`). Reemplazar por la URL definitiva.

## Enlaces salientes
- Curso: https://camino.carlosdelriohealer.com/
- Playlist de Spotify: https://open.spotify.com/playlist/37i9dQZF1DZ06evO0bHrKr
- Podcast Dos Espíritus: https://open.spotify.com/show/1QPdtizp61tOsPRKJBSADo
- 9 álbumes enlazados individualmente a Spotify (carátulas recortadas de Spotify, 600×600 webp)
