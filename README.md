# Portfolio

[![GitHub license](https://img.shields.io/github/license/felixthecat8a/portfolio?color=green)](LICENSE)
[![Sass](https://img.shields.io/badge/styled_with-Sass-cc6699?logo=sass&logoColor=white)](https://sass-lang.com/)
[![Sass Build](https://github.com/felixthecat8a/portfolio/actions/workflows/build-sass.yml/badge.svg)](https://github.com/felixthecat8a/portfolio/actions/workflows/build-sass.yml)

A personal portfolio site designed and built with HTML, Sass, and JavaScript.

> Automatically compiles Sass to CSS on each push using GitHub Actions.

---

## Live Preview

> **Coming Soon**  
> (You can open `index.html` directly in your browser for now)

---

## Getting Started

Clone this repository and open `index.html` in your browser if your interested in making your own profile page.

```bash
git clone https://github.com/felixthecat8a/portfolio.git
cd portfolio
open index.html # or double-click to open manually
```

To compile Sass manually:

```bash
npm install -g sass
sass src/scss:dist/css --style=compressed
```

---

## Build Automation

- Sass is compiled from `src/scss/` to `dist/css` on push using a GitHub Actions workflow.
- The compiled CSS is committed back to the repository automatically.
