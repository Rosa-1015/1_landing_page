# Basic landing page

This is a **Landing Page project (Tasca 1.2)** with three implementations, each in its own branch:

- `vanilla` → Pure HTML + CSS
- `sass` → HTML + Sass
- `tailwind` → HTML + Tailwind CSS

## 📄 Description

A responsive and modular landing page. The goal is to demonstrate the same design using three different styling approaches.

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- [Sass](https://sass-lang.com/) (compiled manually or using Live Sass Compiler in your editor)  
- [Tailwind CSS](https://tailwindcss.com/) via CDN (no build or config required)
---

## ✅ Requirements

To work with any of the three versions, you only need:

- A modern web browser  
- A code editor like [Visual Studio Code](https://code.visualstudio.com/)  
- (Optional) Live Server extension to preview changes  
- (Optional) Live Sass Compiler extension if working on the `sass` branch

> No Node.js or npm required.

---

## 📦 Installation

Follow these steps to get the project up and running:

### 1. Clone the repository

```bash
git clone https://github.com/Rosa-1015/1_landing_page
cd 1_landing_page
```

### 2. Show all branches
```bash
git branch --all
```

### 3. Checkout the version you want to work on

```bash
git checkout vanilla     # or 'sass' or 'tailwind'
```
## 🚀 Run the Project

Just open the index.html file in your browser.
You can also use Live Server (VS Code) for automatic reload on file changes.

## 🎨 Customize Styles

Each branch uses a different styling method:

Vanilla CSS: Edit styles in /assets/css/styles.css

Sass: Modify /assets/css/style.scss and recompile with your preferred method (e.g. Live Sass Compiler)

Tailwind CDN: Tailwind is loaded directly via CDN:

```bash
<script src="https://cdn.tailwindcss.com"></script>
```

You can customize Tailwind utilities inline or in <script> if needed.
