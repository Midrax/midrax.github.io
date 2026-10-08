# Ridam Rahman - Portfolio

This is the source for my personal portfolio at [ridam.it](https://ridam.it/). It brings together my professional game development work, technical projects, education, CV, and a small blog.

I'm a game programmer and computer scientist, currently working at **Rocket Science**. My engineering interests include C++, Unreal Engine, gameplay systems, rendering diagnostics, performance optimization, and tools that help other developers get their work done.

Before joining Rocket Science in July 2026, I worked at **Double Eleven** from April 2021 to April 2026. Earlier in my career, I developed web applications using Angular and Ionic and worked in system administration. That background still informs how I approach software: understand the problem, investigate it carefully, and build a solution that fits the people and systems using it.

## What's on the website

The portfolio includes my contributions to **Crimson Moon**, **Grounded 2**, **Minecraft Dungeons II**, **Fallout 76**, and **RimWorld: Console Edition**, alongside university and game jam projects. Each entry explains my role and contributions, with images and links to the project.

My work on Crimson Moon was carried out while employed by Rocket Science; the game was developed by ProbablyMonsters. It involved rendering fixes, console performance profiling, and support before and after release.

The CV section gives a more detailed account of my experience, technical skills, and progression into games engineering, with a downloadable PDF. The site also includes my education, contact details, and a blog section for more personal writing.

Outside programming, I enjoy creative writing, theatre, DJ-ing, piano, and D&D.

## How the site is built

The website is a static **Jekyll** site hosted on **GitHub Pages**, using **Bootstrap**, **Sass**, and **jQuery**. Its layout started from the Creative theme and has been adapted into my own portfolio, including project modals, image carousels, a glitching header, and a responsive CV page.

The main files are:

| Location | Purpose |
| --- | --- |
| `_config.yml` | Site settings and profile links |
| `_layouts/front.html` | Main page layout and section order |
| `_includes/portfolio.html` | Project tiles, descriptions, and image carousels |
| `_includes/cv.html` | Website version of my CV |
| `_includes/blog.html` | Blog content |
| `_includes/scripts.html` | Scripts and navigation between portfolio, CV, and blog |
| `_sass/_base.scss` | Custom styling and header animation |
| `img/portfolio/` | Project artwork and screenshots |
| `pdf/CV.pdf` | Downloadable CV |

To update a project, edit its entry in `_includes/portfolio.html` and add its images under `img/portfolio/`. New entries go at the top of the portfolio. Keep tile images at **1600 x 900** and carousel images at **1920 x 1080** to match the existing layout.

The website CV and downloadable PDF are separate artifacts, so changes to experience or employment dates should be reflected in both.

## Get in touch

- [Portfolio](https://ridam.it/)
- [GitHub](https://github.com/Midrax)
- [LinkedIn](https://www.linkedin.com/in/ridam-rahman-405b4b155/)
- [Email](mailto:rexridam@gmail.com)

## Theme credits

Built on the [Creative theme for Jekyll](https://github.com/volny/creative-theme-jekyll), based on [Start Bootstrap's Creative theme](https://startbootstrap.com/theme/creative). See `LICENCE` for the included license.
