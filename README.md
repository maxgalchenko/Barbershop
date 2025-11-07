# Barbershop

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/Guide/HTML/HTML5) [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)

</div>

## Overview

Static multi-page barbershop website template. Built with semantic HTML, custom CSS, and a small amount of vanilla JavaScript for modals and interactivity. Useful as a learning artifact and reference for basic layout and UI patterns.

## Key Features

- Multi-page structure: home, catalog, product, and price pages
- Modal interactions: login and map popups with basic JS
- Simple, framework-free stack that is easy to run anywhere

## Tech Stack

HTML5, CSS3, JavaScript (vanilla)

## Architecture

Static site with pages in `index.html` and `app/pages`. Styles live in `app/css`; scripts in `app/js` (`modal-login.js`, `modal-map.js`). No build tooling, database, or server runtime.

## Performance & Accessibility

Lightweight static assets with basic image optimization. Emphasis on semantic markup and keyboard-accessible modals; easy to host via any static server or CDN.

## Prerequisites

- None required (open `index.html` directly)
- Optional: Node.js `>=18` or Python `>=3.8` to run a local static server

## Installation

```bash
git clone git@github.com-personal:maxgalchenko/Barbershop.git
cd Barbershop
```

## Quick Start

```bash
# Option A: open directly
open index.html

# Option B: Python static server (http://localhost:8000)
python3 -m http.server 8000

# Option C: Node static server (requires Node.js)
npx serve -l 8000 .
```

Open http://localhost:8000

## Available Scripts

- None

## Screenshots

![Main](./app/img/screenshots/homepage.png)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/) [![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/) [![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com) ![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
