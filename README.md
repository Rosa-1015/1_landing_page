
# Landing Page SASS Project

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

