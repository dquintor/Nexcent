# Nexcent
# Nexcent Landing Page (HTML + CSS)

This is a web project for a Nexcent Product called "clipboard". We designed the landing page through a figma prototype given and using **semantic HTML** and **responsive CSS** (Flexbox/Grid + media queries).

## Project structure

```
Nexcent/
├── index.html 
├── css/
│   └── styles.css
└── assets/
    ├── blog-images/
    └── client-logos/
    └── icons/
    └── ilustrations/
    └── logo/
    └── social-icons/

```

## How to run

1. Download or clone the project.
2. Open `index.html` in your browser (double click), **or** run a local server:

### Option A: VS Code Live Server
- Right click `index.html` → **Open with Live Server**

### Option B: Python simple server
```bash
python -m http.server 5500
```
Then open: `http://localhost:5500`

## Notes about assets

- All icons and illustrations are referenced as images inside `assets/`. Inside the folder the images/icons/ilustrations are divided by its main porpuse.
  
- If needed Replace the placeholder filenames with your assets:
  - Example: `assets/img/hero-illustration.png`
  - Example: `assets/icons/client-1.png`

## Coder info 

- Full name: Daniela Quinto Rios
- Clan: Turing
- Email: dany.quintorios@gmail.com
- Document ID: 10236626280

## Key implementation details

- HTML uses semantic tags: `header`, `main`, `section`, `footer`.
- CSS uses `:root` variables for colors, typography and sizes.
- Responsive breakpoints:
  - Tablet: `max-width: 900px`
  - Mobile: `max-width: 560px`
- Small micro-interaction: hover transitions on buttons/links/cards and logo hover.

## Credits

Design reference: Assesment RIWI Module 2 
Fonts: Google Fonts (Inter).
