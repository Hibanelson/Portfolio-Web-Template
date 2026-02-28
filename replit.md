# Portfolio Web Template

## Overview
A static HTML/CSS portfolio website template, originally from GitHub Pages (Jekyll). It is served as a plain static site in Replit using Python's built-in HTTP server.

## Project Structure
- `index.html` — Main HTML page
- `css/` — Stylesheets (style.css, all.css for Font Awesome icons)
- `images/` — All image assets
- `webfonts/` — Font Awesome webfont files
- `_config.yml` — Jekyll config (not used in Replit; kept for reference)

## Running the Project
The app is served with:
```
python3 -m http.server 5000 --bind 0.0.0.0
```
Access it on port 5000.

## Tech Stack
- Pure static HTML/CSS
- Font Awesome icons (local)
- No build system or package manager required
