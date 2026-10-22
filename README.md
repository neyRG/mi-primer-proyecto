mi-primer-proyecto
Gastronomía Cubana 🇨🇺

Descripción

Este proyecto consiste en una página web dedicada a la gastronomía cubana. Su objetivo es presentar algunos platos tradicionales de Cuba y mostrar parte de la cultura y las tradiciones relacionadas con su cocina.

El proyecto forma parte de mi proceso de aprendizaje en desarrollo web.

Tecnologías

HTML5
CSS3
Bootstrap 5 (CDN)
Git
GitHub
Visual Studio Code

## Componentes e interacción

- Navbar responsiva de Bootstrap en todas las páginas.
- Carrusel de galería en la página principal y en la receta de congrí.
- Estados `:hover`, `:focus` y `:active` con transiciones para la navegación, enlaces de recetas y controles de galería.

## Evidencia de diseño responsivo

- **CSS Grid y Grid Template Areas:** `style.css` aplica `display: grid` en `.recetas`, `.content-grid` y la introducción. Define áreas con `grid-template-areas` y las asigna mediante `grid-area`; usa columnas flexibles (`1fr`, `2fr`, `minmax(0, 1fr)`) y administra separaciones con `gap`.
- **Mobile-First:** la configuración base apila las secciones en una columna. El `@media (min-width: 1024px)` reorganiza progresivamente la introducción, las recetas y el contenido de las páginas de recetas en columnas para desktop. En anchos intermedios se conserva el flujo vertical, evitando exigir una pantalla grande para leer el contenido.
- **Cobertura de páginas:** `index.html` y los cuatro HTML de `pages/` cargan `style.css` y tienen la navbar responsiva de Bootstrap. El inicio y `pages/congris.html` incorporan además un carrusel; las otras páginas mantienen el diseño adaptativo de la receta.
- **Comprobación local:** se verifican la estructura de Grid, el breakpoint, los enlaces al CSS/CDN, la navbar y las rutas locales de las cinco páginas. El proyecto no incluye una suite automatizada de pruebas.

Cómo empezar

Clonar o descargar el repositorio.
Abrir la carpeta del proyecto en Visual Studio Code.
Abrir el archivo index.html en un navegador web.
Explorar las diferentes secciones de la página.
Estado del proyecto

Proyecto en desarrollo.

Se agregarán nuevas secciones, contenido y mejoras de diseño a medida que avance el proyecto.

Autor

eddie batista