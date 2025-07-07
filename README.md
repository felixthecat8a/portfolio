# Portfolio

[![GitHub license](https://img.shields.io/github/license/felixthecat8a/portfolio?style=for-the-badge&color=green)](LICENSE)
[![Less](https://img.shields.io/badge/styled_with-Less-1d365d?style=for-the-badge&logo=less&logoSize=auto&logoColor=white)](https://lesscss.org/)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/felixthecat8a/portfolio/less-compile.yml?style=for-the-badge&logo=github)

A personal portfolio site designed and built with HTML, Less, and JavaScript.

> Automatically compiles Less to CSS on each push using GitHub Actions.

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

---

## Build Automation

[![Less Compile](https://github.com/felixthecat8a/portfolio/actions/workflows/less-compile.yml/badge.svg)](https://github.com/felixthecat8a/portfolio/actions/workflows/less-compile.yml)

- Sass is compiled from `src/less/` to `dist/css` on push using a GitHub Actions workflow.
- The compiled CSS is committed back to the repository automatically.
