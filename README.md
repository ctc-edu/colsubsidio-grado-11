# Yo decido · Grado 11 — Crack the Code (Colsubsidio)

Sitio del curso **Investigación & Lanzamiento IA — "Yo decido"** (Grado 11), listo para publicar.

El punto de entrada es **`index.html`**: muestra el mapa del curso (Bienvenida → Bloque 1 → Bloque 2 → Demo Day) y enlaza cada material.

## Qué hay en el repo

```
index.html                                     ← portada (mapa del curso)
01-bienvenida.html                             ← autocontenido
02-bloque1-parte1-pregunta-y-busqueda.html     ← autocontenido
03-bloque1-parte2-sigue-y-triangula.html       ← autocontenido
04-bloque1-parte3-reescribe-apa-organiza.html  ← autocontenido
05-bloque1-parte4-informe-y-decision.html      ← autocontenido
06-bloque2-parte1-evidencia-marca-cv.html      ← autocontenido
07-bloque2-parte2-linkedin-carta-pitch.html    ← autocontenido
08-bloque2-parte3-portafolio-y-entrega.html    ← autocontenido
09-demo-day.html                               ← autocontenido
portafolio-de-ejemplo.html                     ← usa support.js + colors_and_type.css + assets/
support.js                                     ← runtime para el portafolio de ejemplo
colors_and_type.css                            ← estilos del portafolio de ejemplo
assets/valentina.jpg                           ← imagen del portafolio de ejemplo
```

- Los **10 materiales del curso** son autocontenidos: funcionan solos, no dependen de ningún archivo externo.
- El **portafolio de ejemplo** usa `support.js`, `colors_and_type.css` y `assets/valentina.jpg` (incluidos). *Nota: el `colors_and_type.css` de este repo es una versión simplificada —sin el design system `_ds/` interno de CTC—, así el portafolio renderiza solo; la tipografía del cuerpo usa una fuente de sistema.*

## Publicar en GitHub Pages

1. Sube todo el contenido de esta carpeta a la raíz del repo (arrastrar y soltar en github.com sirve).
2. En el repo: **Settings → Pages**.
3. En **Source**, elige la rama `main` y la carpeta `/ (root)`. Guarda.
4. En uno o dos minutos el sitio queda en `https://<usuario>.github.io/<repo>/`.

## Notas de versiones

De los materiales con varias versiones se usó la más reciente: **Bloque 2 · Parte 1** = `offline_1`, **Bloque 2 · Parte 2** = `offline_2`. Si tienes una versión más nueva de alguno, reemplaza el archivo con el mismo nombre.

## Guiones de Pixie

Los guiones de Pixie (currícula, evaluación y system prompt) son la base de conocimiento del asistente; se gestionan aparte y no se publican en este sitio.
