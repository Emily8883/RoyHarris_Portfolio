# Roy Harris Website

Static multi-page front-end website for Roy Harris, showcasing martial arts instruction, defensive tactics, arrest and control training, resources, FAQ content, and blog articles.

## Overview

This repository contains a static website built with HTML, CSS, JavaScript, fonts, and image assets. There is no build step required, and the site can be served from any static web server or opened directly in a browser.

## Pages

- `index.html` — home page
- `indexpersonal2.html` — alternate homepage layout
- `about.html` — about page
- `about2.html` — alternate about page
- `blog.html` — blog index page
- `blog-article-good-instructor.html` — blog article
- `blog-article-importance-bridge.html` — blog article
- `blog-article-intercepting-hand.html` — blog article
- `faq.html` — frequently asked questions page
- `resources.html` — resources page
- `video-sound.html` — media/demo page
- `accordions.html` — accordion demo page
- `404.html` — custom error page

## Project Structure

- `css/` — stylesheets
- `js/` — JavaScript files and plugins
- `fonts/` — local font assets and icon fonts
- `img/` — main image assets
- `icon/` — icon and social assets
- `scss/` — Sass source files
- `src/` — source images used in page sections

## Local Preview

Open `index.html` directly in a browser, or use a static server to preview the site.

Example:

```bash
npx serve
```

Then open the local URL shown in the terminal.

## Notes

- Keep relative paths intact when moving or renaming assets.
- Update navigation and shared UI elements in each HTML file if menu structure changes.
- Primary styles are in `css/main.css` and `css/roy-harris.css`.
- Homepage hero content is defined in `index.html` and `indexpersonal2.html`.

## Contact

The site references the email address `roy@royharris.com`.
