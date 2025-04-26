# Landing – Economía Monetaria y Financiera

Landing page estática que cumple los checkpoints del módulo de desarrollo web.  
Incluye HTML5, Bootstrap 5, SCSS (Sass), Flexbox, CSS Grid, animaciones y RWD.

# Estructura Sass (7-1 pattern)

settings/  → variables, mixins
tools/     → placeholders
generic/   → reset
elements/  → estilos base h1…h6, a, p
objects/   → layout genérico, grid
components/→ navbar, hero, cards, timeline…
utilities/ → helpers (m-*, p-*, text-center…)

## Requisitos previos
* Node ≥ 18
* Git

## Instalación

```bash
git clone https://github.com/tu-usuario/monetaria-landing.git
cd monetaria-landing
npm install
npm run sass   # compila SCSS y observa cambios
```