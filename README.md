# Landings AHA

Landings públicas de AHA. Cada carpeta es una landing con su propio enlace:
`https://mareaco.github.io/landings/<carpeta>/`

- Las respuestas se guardan en Supabase (proyecto **Landings**, tabla `respuestas`), etiquetadas con el nombre de la carpeta en la columna `formulario`.
- La clave que aparece en las páginas es la clave **pública** de Supabase: solo permite enviar respuestas, no leerlas.
- `_plantilla/` es la base para crear landings nuevas; no recibe respuestas.

Para crear una landing nueva: copiar `_plantilla/` a una carpeta nueva, cambiar `FORMULARIO`, los textos y `PREGUNTAS`, y publicar.
