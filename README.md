# Nexcent Landing Page - Responsive Landing page
Nextcent is a fully responsive landing page developed using semantic HTML5 and CSS, based on a figma designed. The objective of this project is to demonstrate strong fundamentals in front-end layout, responsiveness, code organization and maintability.

# Project Objectives:
- Apply semantic HTML for accessibility and maintainability
- Implement responsive layouts usign modern CSS techniques
- Maintain a clean and scalable file structure
- Write readable, reusable, and well-structured CSS

# Technologies used 
- HTML5
- CSS

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

# Structure rationable
- Separation of concerns: markup, styling and assets are clearly isolated
- Scalability: asset categories are separated for easy expansion
- Maintainability: predictable structure suitable for larger projects

# HTML Architecture
The HTML file follows a semantic and hierarchical structure:

- "header" Contains the navigation and branding elements
- "main" Encapsulates all primary content sections, including: 
    - Hero section
    - Client logos
    - Feature descritions
    - Blog or informational-sections
    - Call to action blocks
- "footer" contains
- Logical section grouping using "section"
- Meaningful class naming conventions
- No inline styles
- Clean indentation and readable markup

# CSS Architecture
- Centralized styling in a single styles.css file
- Modular section-based styling using class selectors
- Reusable utility patterns through shared class rules

CSS custom properties defined at the :root level for: 
- Color palette
- Font Families
- Common spacing values

This approach allows:
- Easier theme adjustments
- Consistent visual identity
- Reduced Repetion

## Layout System 

# Flexbox
Used for:
- Navigation alignment
- Horizontal and vertical centering
- Card-based components

# CSS Grid 
Used where:
- Multi-column Layouts are required
- COntent needs consistent spacing across rows and columns

# Responsiveness 
The layout is fully responssive and adapts across devices using media queries

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

## Author info 

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

