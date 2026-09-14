# Personal Website

A static portfolio site for GitHub Pages.

## Site structure

- `index.html` contains the introduction and links to the work pages.
- `printmaking.html` contains the three printmaking process photographs.
- `pigeons.html` contains the pigeon learning research description and photograph.
- `interactions/index.html` contains links to interaction design and research projects.
- `interactions/` contains the detail pages for Audible Feelings, Exploring Sound Effects, and Audio Canvas.
- `styles.css` controls the shared typography, layout, and responsive styles.
- `assets/images/` stores portfolio images.

## Edit content

- Update the introduction and destination links in `index.html`.
- Add a printmaking image by duplicating a `.print-item` figure in `printmaking.html`.
- Add an interaction by creating a detail page in `interactions/`, then add a matching `.interaction-entry` link in `interactions/index.html`.
- Keep image paths relative to each page. Images in `printmaking.html` begin with `assets/images/`. Images in `interactions/index.html` begin with `../assets/images/`.

## Fonts

The site uses a system monospace stack for its text-led layout, so it works without loading external fonts.

## Deploy on GitHub Pages

1. Push this folder to a GitHub repository.
2. In GitHub, go to `Settings` then `Pages`.
3. Set the source to the main branch and root folder.
4. Save. GitHub Pages serves `index.html` automatically.

No server-side code or build step is required.
