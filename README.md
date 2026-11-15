# Turtle Studio

Website for Turtle Studio, the design practice of Saloni Dwivedi: product design for enterprise AI and B2B teams.

A static site (HTML, CSS and a little JavaScript, no build step), hosted on GitHub Pages.

## Structure

- `index.html`: the whole page (styles and scripts are inline)
- `assets/logo.svg`: the Turtle Studio wordmark
- `assets/hero/`: product screens that rotate in the hero
- `assets/work/`: Selected work backgrounds, videos and the table prototype
- `favicon.svg`, `apple-touch-icon.png`, `assets/og.png`: icons and the link preview image

## Editing

Edit `index.html` and push to `main`. GitHub Pages republishes in about a minute.

To preview locally, run `python3 -m http.server` in this folder and open http://localhost:8000. The table prototype needs a local server and won't load from a double-clicked file.
