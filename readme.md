# Calculator

## Calculator made with JavaScript, TailwindCSS, Vanila CSS and HTML

---

### There are two versions for the calculator which display multiple styling with Vanila css in v1.0 and TailwindCSS in v2.0

---

## Key Features

### v1.0

- Used Mordern JavaScript (ES6) features like Class, Construtor, This keyword, Switch statement, ETC.
- Used vanila CSS utilities like grid, flex, hover, border image source and clip, ETC.
- used HTML data keywords

### v2.0

- rebuild the UI with TailwindCSS
- Added Dark/light mode
- fetches the same script used for v1.0

---

### File Structure

- index.html (src HTML v2.0)
- css (src TailwindCSS v2.0)
  - dist (output src for TailwindCSS v2.0)
    - output.css (output file for TailwindCSS v2.0)
  - src (input src for TailwindCSS v2.0)
    - input.css (input file for TailwindCSS v2.0)
- js (src JavaScript v1.0 , v2.0)
  - script.js (main script for calculation and data output)
  - darkMode.js (toggle script for TailwindCSS Dark mode v2.0)
- v1.0 (src v1.0)
  - index.html (src HTML v1.0)
  - css
    - style.css (src CSS v1.0)

### To Build

1. After cloning the repo

```
npm install
```

2. Build tailwind

```
npx tailwind -i ./css/src/input.css -o ./css/dist/output.css --watch
```
