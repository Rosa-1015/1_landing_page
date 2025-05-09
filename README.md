
# Landing Page SASS Project

## Table of Contents

- [Description](#description)
  
- [Project Structure](#project-structure)
  
- [Installation](#installation)
  
- [Usage](#usage)
  
- [Technologies Used](#technologies-used)

## Description

Sprint 1.2. SASS

This is a responsive landing page built using HTML5 and SASS. It is designed with a clean structure and modular SCSS.

 ### Features

- Fully responsive layout

- Clean and semantic HTML5

- Modular SASS structure

- Easy to customize and extend

## Project Structure 

📦️ 1_LANDING_PAGE
┣ 📂assets
┃ ┣ 📂css
┃ ┃ ┗ 📄 style.css
┃ ┣ 📂images
┃ ┃ ┗ 📂icons
┃ ┗ 📂scss
┃   ┣ 📂partials
┃   ┣ 📄 style.scss
┃   ┗ 📄 style.css.map
┣ 📄 index.html
┗ 📄 README.md

## Installation

Follow these steps to set up the project locally:

### 1. Clone this repository:

```bash
git clone https://github.com/Rosa-1015/1_landing_page
```

### 2. Navigate to the project folder:

```bash
cd 1_landing_page
```

### 3. Compile SCSS to CSS
You have two options:

**Option A: Using the terminal (requires SASS installed globally)**
Install SASS globally if you haven't already:
```
npm install -g sass
```
Then run the compiler in watch mode:

```
sass src/scss/main.scss dist/css/style.css --watch
```

**Option B: Using Live Sass Compiler in VS Code**

1. Install the Live Sass Compiler extension in Visual Studio Code.

2. Open the project folder in VS Code.

3. Click the "Watch Sass" button in the bottom right corner.

4. The compiled CSS will be generated automatically.

### 4. Open the landing page
You can open index.html directly in your browser, or use the Live Server extension in VS Code for live preview.

## Technologies used 

- HTML5 – For semantic and accessible page structure

- SASS (SCSS) – For modular, maintainable, and scalable styling

- CSS3 – Compiled from SCSS for styling the layout and components

- Visual Studio Code – Recommended code editor

- Live Sass Compiler (optional) – For real-time SCSS compilation

- Live Server (optional) – For local development with live reload
