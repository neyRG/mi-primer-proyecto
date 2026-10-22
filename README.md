# Gastronomía Cubana

Sitio web educativo que presenta platos tradicionales de Cuba y recetas de ropa vieja, congrí, tostones y cascos de guayaba. El proyecto busca compartir sabores y contexto de la cocina cubana a través de una experiencia clara y adaptable a distintos dispositivos.

## Contenido

- Página principal con una introducción, platos famosos y una galería interactiva.
- Cuatro páginas con ingredientes e instrucciones de recetas.
- Navegación adaptable y diseño responsive para móvil, tablet y escritorio.
- Transiciones de interfaz y animación propia de entrada en los títulos.
- Animate.css en la galería de inicio y compatibilidad con `prefers-reduced-motion`.

## Tecnologías

- HTML5 y CSS3 (CSS Grid, media queries y animaciones).
- Bootstrap 5 para la navegación y los carruseles.
- Animate.css para una animación de la galería.
- Git y GitHub para el control de versiones y la colaboración.

## Estructura

```text
.
├── index.html
├── style.css
├── pages/
│   ├── congris.html
│   ├── guayaba.html
│   ├── ropa-vieja.html
│   └── tostone.html
└── assets/
    └── img/
```

## Instalación y visualización

No requiere instalación de dependencias ni un proceso de compilación. Para verlo localmente:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/neyRG/mi-primer-proyecto.git
   ```

2. Abre la carpeta del proyecto en Visual Studio Code.
3. Abre `index.html` en un navegador. Bootstrap y Animate.css se cargan por CDN, por lo que se necesita conexión a Internet para esos recursos.

## Colaboración

El flujo de trabajo recomendado es **Feature Branching**: registrar cada tarea en un Issue, actualizar `main`, crear una rama con un nombre descriptivo, desarrollar y verificar el cambio, y abrir un Pull Request hacia `main`. Los cambios se revisan en el PR antes de integrarlos; después del merge, se actualiza la rama principal local.

Para esta evolución, la rama de trabajo es `feature/responsive-animations`. El archivo `.gitignore` excluye archivos de configuración local, metadatos del sistema y logs; los recursos de imagen utilizados por el sitio permanecen versionados.

## Verificación responsive

Las cinco páginas se comprobaron en anchos de 375, 768 y 1280 píxeles, sin desbordamiento horizontal. También se verificó el menú móvil y el modo de movimiento reducido del navegador. El proyecto no incluye una suite automatizada de pruebas.

## Autor

Eddie Batista
