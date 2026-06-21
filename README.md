# Bubbles & Sun — website

Static one-page site for **Bubbles & Sun**, a laundromat + tanning salon at
279 Main St, Hudson Falls, NY. Sister rental business: TNT Rentals.

## Files
- `index.html` — the website (self-contained: HTML + CSS + JS in one file).
- `brand-assets.html` — open in a browser to download the Facebook cover, logo, and icon PNGs.
- `assets/generated/` — cartoon brand images (sun + pink bubble, the pink building, etc.).
- `.nojekyll` — tells GitHub Pages to serve the files as-is.

## Publishing on GitHub Pages
1. Push this folder to the repo (it must contain `index.html` at the root).
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)**. Save.
4. The site goes live at `https://<user>.github.io/Bubbles/` in a minute or two.

## Editing
Open `index.html` in any text editor. Hours, phone, address, and specials are
plain text near the top of the `<body>`. No build step — just edit and re-push.
