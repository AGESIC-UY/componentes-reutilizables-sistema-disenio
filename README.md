# Sistema de Diseño

Biblioteca de tokens, estilos (SCSS/CSS), íconos y componentes del Sistema de Diseño del Estado uruguayo.

**Portal de documentación:** [sistemadiseño.agesic.gub.uy](https://sistemadiseño.agesic.gub.uy)

## Qué incluye

- `scss/` — Código fuente en Sass (`tokens/`, `base/`, `layouts/`, `components/`, `utilities/`).
- `recursos/css/main.css` — Hoja de estilos compilada lista para usar.
- `recursos/dist/sprites.svg` — Sprite SVG de íconos compilado (fuentes en `recursos/iconos/`).
- `recursos/fonts/` — Tipografías web (`Open Sans` y `Sora`).
- `recursos/ia/` — Guías e instrucciones para desarrollo asistido por IA (ver `recursos/ia/SDU-instrucciones-generales-para-ia.md`).
- `scripts/` — Módulos JavaScript para componentes interactivos (`Modal`, `Dropdown`).
- `comp/` — Ejemplos de marcado HTML/PHP de cada componente y estilos globales.

## Uso rápido en un proyecto

1. Incluí `recursos/css/main.css` en tu proyecto (manteniendo la carpeta `recursos/fonts/` accesible de forma relativa para que carguen las tipografías).
2. Para componentes interactivos (modales y desplegables), incluí `scripts/main.js` como módulo (`<script type="module" src="scripts/main.js"></script>`).
3. Para íconos, incluí o referenciá el sprite `recursos/dist/sprites.svg`.
4. Si trabajás con Sass, podés importar directamente desde `scss/main.scss` o usar los tokens de `scss/tokens/`.

## Desarrollo asistido por IA

En `recursos/ia/` se encuentran las instrucciones y especificaciones pensadas como contexto para asistentes de IA:

- `recursos/ia/SDU-instrucciones-generales-para-ia.md`: reglas generales, tokens CSS, marcado semántico, clases BEM y lineamientos de accesibilidad.