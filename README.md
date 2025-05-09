
# Landing Page SASS Project

## Table of Contents

- [Description](#description)
  
- [Project Structure](#project-structure)
  
- [Installation](#installation)
  
- [Usage](#usage)
  
- [Technologies Used](#technologies-used)
  
- [Screenshots](#screenshots)

## Description

Sprint 1.1. HTML i CSS amb Flex

A simple landing page created with only HTML and CSS, without frameworks or JavaScript. Ideal as a basic example for practicing static web design. It's part of a web development sprint designed to practice semantic structure, custom styles, and clean design.

## 📁 Estructura del proyecto

```
landingpage-sass/
│
├── css/                  # Carpeta donde se compila el CSS final
│
├── scss/                 # Código fuente SASS
│   ├── partials/         # Partials organizados
│   │   ├── _variables.scss
│   │   ├── _globals.scss
│   │   └── _navbar.scss
│   └── style.scss        # Archivo principal que importa los partials
│
├── index.html            # HTML actualizado enlazado a style.css
└── README.md             # Instrucciones para compilar con Live Sass Compiler
```

## 🚀 Cómo compilar el SCSS

1. Abre Visual Studio Code en esta carpeta.
2. Asegúrate de tener instalada la extensión "Live Sass Compiler".
3. Abre `scss/style.scss` y haz clic en "Watch Sass" en la barra inferior.
4. El CSS generado se guardará automáticamente en `css/style.css`.

