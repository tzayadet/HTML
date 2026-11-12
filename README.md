# Matrix Visual Experiments

Small personal frontend repository containing two standalone Matrix-inspired banner prototypes built with HTML, CSS and Canvas.

## Live preview

When GitHub Pages is enabled for this repository, the landing page is available at:

`https://tzayadet.github.io/HTML/`

The landing page links to each independent experiment:

- [Animated Matrix](animatedmatrix.html): Canvas-based digital-rain animation with a text overlay.
- [Matrix Banner](matrix1.html): static banner composition with gradients and a subtle Matrix-inspired texture.

## Run locally

Open `index.html` in a browser, or serve the repository directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Stack

- HTML5
- CSS3
- JavaScript
- Canvas API

These are visual prototypes, not production applications.

## Publish the showcase

To publish the static site, open **Settings → Pages** and select **GitHub Actions** as the build source. Then add the repository Actions variable `ENABLE_PAGES=true` under **Settings → Secrets and variables → Actions → Variables**. A push to the repository root HTML files or a manual workflow run will deploy the site. Until Pages is enabled and the variable is set, the preview remains source-only.
