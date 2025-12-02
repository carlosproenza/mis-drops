# Drop 03 — YOKONO (Preview)

Contenido de la carpeta drops/drop03:
- index.html -> Página del drop (alineada con la estructura y estilos de los otros drops)
- YOKONO WERO copia.png -> Portada del drop (archivo con espacios, usado tal cual en el HTML)
- hero.svg -> placeholder SVG (opcional)
- release-hero.css -> estilos mínimos locales para el hero

Cómo probar localmente:
- Desde la raíz del repo, servir la carpeta drops/drop03 con un servidor estático:
  - npx serve drops/drop03
  - o: python3 -m http.server --directory drops/drop03 8000
- Abrir en navegador: http://localhost:5000 (o el puerto que indique el servidor)

Notas:
- La página utiliza ../../style.css para heredar estilos globales y mantiene la misma jerarquía y clases (feed-eyebrow, feed-title, feed-meta, drop-hero, drop-content) para consistencia visual.
- Si prefieres renombrar la portada para quitar espacios, actualiza las referencias en index.html e index.html (raíz).
