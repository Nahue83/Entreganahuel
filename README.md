# Delicateces Sion — Entrega Coderhous

**Delicateces Sion**.

# Delicateces Sion

Este proyecto lo desarrollé para la cursada de **Desarrollo Web en Coderhouse**.  
La idea fue aplicar los contenidos vistos en clase: HTML, CSS, Bootstrap y Sass, con foco en la maquetación, el responsive y las buenas prácticas de organización de código.

---

## 🚀 Tecnologías utilizadas
- **HTML5** para la estructura del sitio  
- **CSS3 + Bootstrap 5** para estilos base y componentes  
- **Sass (SCSS)** con variables, mixins, extend, anidación y partials  
- **Animaciones** con `transition`, `transform` y `@keyframes`  
- **Git + GitHub Pages** para control de versiones y despliegue online  

---

## 📂 Estructura del proyecto
- `/scss/` → Archivos fuente de Sass organizados en partials (`_variables`, `_mixins`, `_header`, `_footer`, etc.)  
- `/css/styles.css` → Archivo CSS compilado desde Sass (lo que se usa en producción)  
- `/pages/` → Páginas secundarias (`contacto.html`, `sobremi.html`, etc.)  
- `/assets/` → Imágenes y recursos multimedia  
- `index.html` → Página principal del sitio  

---

## 📱 Responsive design
Se trabajó con enfoque **mobile-first**.  
Las media queries están definidas con `min-width` y en orden creciente:

```scss
@media (min-width: 576px) { ... }
@media (min-width: 768px) { ... }
@media (min-width: 1024px) { ... }
