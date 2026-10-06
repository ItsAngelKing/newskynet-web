---
description: "Use when styling or adjusting the NewSkyNet header, navigation, logo, or related responsive CSS."
applyTo: ["index.html", "src/style.css", "src/img/**"]
---

# Estilo del header

- Conserva el contenido, el texto en español y los enlaces actuales del header. Prioriza resolver la presentación en `src/style.css` y evita cambios de estructura salvo que sean necesarios para una semántica HTML válida.
- Usa `src/img/logo.jpg` como referencia visual del color: toma el azul marino oscuro del fondo del logo como base y el cian brillante como acento. Comprueba el archivo real antes de fijar colores CSS para que el fondo del header armonice con el logo.
- Mantén el logo legible y proporcionado; evita deformarlo o introducir un fondo que choque con el fondo integrado en la imagen.
- Asegura que navegación y marca sigan siendo legibles, utilizables con teclado y adaptables a pantallas estrechas, sin desbordes.
- Comprueba `index.html` en un navegador en tamaños de escritorio y móvil; este proyecto no documenta un comando de pruebas.