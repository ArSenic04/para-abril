# Cómo agregar tus GIFs

El sitio busca estos 4 archivos en esta carpeta:

- `cuddle.gif` — en la sección de la pregunta
- `kiss.gif` — en la sección de celebración
- `cuddle2.gif` — en la sección de Escorpio
- `hug.gif` — en la sección de distancia (Montreal ↔ Minnesota)

Si un archivo no existe, el sitio muestra automáticamente un emoji grande en su lugar — nada se rompe.

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
