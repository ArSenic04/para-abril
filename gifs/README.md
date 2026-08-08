# Cómo agregar tus GIFs

El sitio busca estos archivos en esta carpeta:

- `Blow_kiss.gif` — en la sección de la pregunta
- `kiss.gif` — en la sección de celebración
- `cuddle_love.gif` — en la sección de Escorpio
- `where_tonow.gif` — en la sección de distancia (Montreal ↔ Minnesota)
- `intense_gif.gif`, `intense_gif1.gif` ... `intense_gif6.gif` — en la galería con candado "Mis favoritos" (solo se ven después de responder las preguntas)

Si un archivo no existe, el sitio muestra automáticamente un emoji grande en su lugar — nada se rompe.

Para agregar más GIFs a la galería "Mis favoritos", solo pon el archivo aquí y agrega su nombre a la lista `INTENSE_GIFS` en `index.html`.

## Pasos para agregar un GIF real (gratis, sin API keys)

1. Ve a [giphy.com](https://giphy.com) o [tenor.com](https://tenor.com) y busca el GIF que quieras (ej. "cute couple cuddle").
2. Haz clic derecho sobre el GIF → "Guardar imagen como..." (o descárgalo desde el botón de compartir/descargar del sitio).
3. Renombra el archivo exactamente como uno de los nombres de arriba (ej. `kiss.gif`).
4. Ponlo en esta carpeta (`para-abril/gifs/`).
5. Sube los cambios:
   ```
   git add gifs/
   git commit -m "Agregar gifs"
   git push
   ```

Tamaño recomendado: menos de 3MB por GIF para que cargue rápido en el celular.
