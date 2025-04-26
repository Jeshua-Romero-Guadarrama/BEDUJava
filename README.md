# Landing – Economía Monetaria y Financiera

Landing page estática que cumple los checkpoints del módulo de desarrollo web.  
Incluye HTML5, Bootstrap 5, SCSS (Sass), Flexbox, CSS Grid, animaciones y RWD.

## Estructura del proyecto 

```
economia-monetaria-financiera/
├── public/
│   ├── index.html
│   ├── teoria.html
│   ├── crisis.html
│   ├── ataques.html
│   ├── regulacion.html
│   ├── fundamentos.html
│   ├── mercados.html
│   ├── cartera.html
│   ├── derivados.html
│   ├── econometria.html
│   ├── assets/
│   │   ├── img/
│   │   │   └── hero.jpg        # reemplázala por tu imagen de portada
│   │   └── css/
│   │       └── style.css       # generado automáticamente
│   └── js/
│       └── app.js
├── src/
│   └── scss/
│       ├── 1-settings/
│       │   ├── _variables.scss
│       │   └── _mixins.scss
│       ├── 2-tools/
│       │   └── _placeholders.scss
│       ├── 3-generic/
│       │   └── _reset.scss
│       ├── 4-elements/
│       │   └── _typography.scss
│       ├── 5-objects/
│       │   ├── _layout.scss
│       │   └── _grid.scss
│       ├── 6-components/
│       │   ├── _navbar.scss
│       │   ├── _hero.scss
│       │   ├── _card.scss
│       │   ├── _timeline.scss
│       │   └── _footer.scss
│       ├── 7-utilities/
│       │   └── _utilities.scss
│       └── style.scss          # punto de entrada
├── .gitignore
├── package.json
├── netlify.toml
└── README.md
```

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