# 🏝️ La Isla del Saber

Juego de la oca educativo para clase (2 a 8 equipos). Todo está en un único archivo, `index.html`, sin dependencias ni conexión a internet.

## Cómo jugar
1. Elige el número de equipos y pulsa **¡A jugar!**
2. El equipo en turno tira el dado y su ficha avanza.
3. Se pulsa la casilla que late y sale una pregunta al azar.
4. El profesor valida con **✔ Acertaron** o **✘ Fallaron** (el botón **👁 Ver respuesta** muestra la respuesta modelo).
5. Si aciertan se quedan; si fallan vuelven a la casilla anterior. Gana el primer equipo que llegue a la meta.

## Publicarlo en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `isla-del-saber`).
2. Sube `index.html`, `.nojekyll` y este `README.md`.
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
4. En un par de minutos estará en `https://TU-USUARIO.github.io/isla-del-saber/`.

## Cambiar las preguntas
Botón **✏️ Preguntas** dentro del juego. Una pregunta por línea:

`tipo | pregunta | respuesta | opciones separadas por ; (solo en test) | nº de imagen 0-9 (opcional)`

Tipos: `def`, `img`, `test`, `breve`, `corta`. Se guardan en el navegador de cada equipo/ordenador (no en el repositorio). Para cambiar las preguntas por defecto para todos, edita el texto de la variable `DEF` dentro de `index.html`.
