# Delicateces Sion — Entrega Coderhous

Este repositorio contiene el sitio estático del proyecto **Delicateces Sion**.

## Tech
- HTML5 + CSS3 (con Bootstrap 5)
- SCSS estructurado por _partials_ (`scss/`): variables, mixins, header, footer, pages y responsive.
- Animaciones con `transition`, `transform` y `@keyframes`.

## Estructura
- `index.html` + páginas en `pages/`
- Estilos en `css/styles.css`
- Fuentes e imágenes en `assets/`
- SCSS fuente en `scss/` .

## Responsive
**mobile-first**. Las _media queries_ usan `min-width` y van de menor a mayor:

```css
@media (min-width: 576px) { ... }
@media (min-width: 768px) { ... }
@media (min-width: 1024px) { ... }
```

## Accesibilidad
- Atributos `role` y `aria-label` en navegación y footer.
- Foco visible en enlaces del footer.
- Imágenes fluidas con `max-width: 100%` y `height: auto`.