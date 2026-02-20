# Daniel Cregg - Personal Portfolio Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A modern, responsive personal portfolio website showcasing skills, projects, and professional background. Hosted on GitHub Pages with a custom domain.

## Overview

This repository contains the source code for [danielcregg.is-a.dev](https://danielcregg.is-a.dev), a single-page portfolio website built with vanilla HTML, CSS, and JavaScript. The site features a clean gradient design, skill tags, project cards, and social links. It also includes an interactive dancing robots canvas animation powered by a physics-based verlet integration engine.

## Features

- **Responsive Design** -- Mobile-friendly layout with CSS Grid and Flexbox
- **Modern UI** -- Gradient backgrounds, card-based project showcase, and smooth hover transitions
- **Interactive Animation** -- Canvas-based dancing robot figures with drag-and-drop interaction
- **Custom Domain** -- Configured with `danielcregg.is-a.dev` via CNAME
- **Jekyll Integration** -- Supports GitHub Pages Jekyll themes and Stastic CMS for content editing

## Prerequisites

- A web browser (Chrome, Firefox, Safari, or Edge)
- [Git](https://git-scm.com/) for cloning the repository
- A GitHub account (for GitHub Pages deployment)

## Getting Started

### Installation

```bash
git clone https://github.com/danielcregg/danielcregg.github.io.git
cd danielcregg.github.io
```

### Usage

Open `index.html` directly in a browser, or serve locally with any static file server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve .
```

Then visit `http://localhost:8000` in your browser.

To deploy, push changes to the `main` branch and GitHub Pages will automatically publish the site.

## Tech Stack

- **HTML5** -- Semantic markup and page structure
- **CSS3** -- Styling, gradients, responsive layout, and animations
- **JavaScript** -- Interactive canvas animation with physics simulation
- **Jekyll** -- GitHub Pages static site generator
- **GitHub Pages** -- Hosting and deployment

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
