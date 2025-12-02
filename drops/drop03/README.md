# Drop 03 — YOKONO (Preview)

Contenido de la carpeta drops/drop-03:
- index.html -> Demo estática (abrir en navegador o servir con servidor estático)
- release-hero.css -> Estilos del hero
- hero.svg -> Placeholder para la portada

Cómo probar localmente:
- Desde la raíz del repo, servir la carpeta drops/drop-03 con un servidor estático:
  - npx serve drops/drop-03
  - o: python3 -m http.server --directory drops/drop-03 8000
- Abrir en navegador: http://localhost:5000 (o el puerto que indique el servidor)

Notas:
- Reemplaza hero.svg por la portada real y actualiza release-hero.css si cambia nombre o formato.
- Si tu sitio genera rutas desde otra parte, integra el HTML o el componente donde corresponda.