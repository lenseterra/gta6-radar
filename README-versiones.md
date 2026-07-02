# Versiones de referencia — GTA6 Intel

## version-noticias-cortas
- **SHA:** 87c9e77ee0189f2b3d255b89b22742d7348af7e1
- **Fecha:** 2 Jul 2026
- **Descripción:** Noticias integradas directamente en el panel del sitio principal como tarjetas cortas. Sin páginas individuales por artículo.
- **Cómo restaurar:** `git checkout 87c9e77ee0189f2b3d255b89b22742d7348af7e1 -- index.html`

## version-articulos (actual desde Jul 2026)
- Cada noticia tiene su propia página HTML en `/noticias/`
- El panel de noticias del sitio principal muestra cards con link a cada artículo
- URL ejemplo: `gta6latino.com/noticias/gta6-sin-doblaje-espanol.html`
