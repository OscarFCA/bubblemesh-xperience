# BubbleMesh Xperience — Landing

Landing page de conversión de **BubbleMesh Xperience**, la submarca de BubbleMesh
para el sector de turismo, experiencias y entretenimiento en México.

🔗 **Producción (futuro):** https://xperience.bubble-mesh.com
🔗 **GitHub Pages:** https://oscarfca.github.io/bubblemesh-xperience/

## Stack

Sitio 100% estático — sin frameworks ni build step.

- `index.html` — landing completa (10 secciones, metodología Mercatitlán)
- `css/styles.css` — sistema de diseño (tokens del brandbook DESIGN.md)
- `js/main.js` — menú móvil, acordeón FAQ y reveal on scroll (vanilla JS)
- `assets/img/` — imágenes optimizadas en `.webp` (responsive con `srcset`)
- `assets/video/hero.mp4` — video de fondo del hero
- `assets/logo/` — logotipo e iconos

## SEO / Rendimiento

- Meta tags, Open Graph y Twitter Cards completos
- Datos estructurados JSON-LD (`ProfessionalService` + `FAQPage`)
- `sitemap.xml`, `robots.txt`, `site.webmanifest`, favicons
- Imágenes en WebP (reducción de ~31 MB a ~0.8 MB), `loading="lazy"`, `srcset`
- Peso total del sitio: ~3.4 MB (2.5 MB del video hero)
- Accesibilidad: `lang="es"`, navegación por teclado, `alt` descriptivos, `prefers-reduced-motion`

## Desarrollo local

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Conversión

CTA único: agendar diagnóstico gratuito de 30 min vía Calendly.

---

© 2026 BubbleMesh · Una submarca de BubbleMesh
