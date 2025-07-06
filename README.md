# Felix Ochoa – Portfolio

[![GitHub license](https://img.shields.io/github/license/felixthecat8a/portfolio?style=for-the-badge&color=green)](LICENSE)
[![Sass](https://img.shields.io/badge/styled_with-Sass-cc6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/felixthecat8a/portfolio/build-sass.yml?style=for-the-badge&logo=github)

A personal portfolio site designed and built with HTML, Sass, and JavaScript to showcase my work in STEM education, Arduino development, and full-stack engineering design.

> Automatically compiles Sass to CSS on each push using GitHub Actions.

---

## Live Preview

> **Coming Soon**  
> (You can open `index.html` directly in your browser for now)

---

## About Me

I'm Felix — an educator with over 18 years of experience teaching technology and mathematics. I specialize in hands-on STEM education, robotics, and engineering design.

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

[![Sass Build](https://github.com/felixthecat8a/portfolio/actions/workflows/build-sass.yml/badge.svg)](https://github.com/felixthecat8a/portfolio/actions/workflows/build-sass.yml)

- Sass is compiled from `src/scss/` to `dist/css` on push using a GitHub Actions workflow.
- The compiled CSS is committed back to the repository automatically.

---

## Contact

You can find more of my work on [GitHub](https://github.com/felixthecat8a).

---

## License

This project is open source and available under the [MIT License](LICENSE).
