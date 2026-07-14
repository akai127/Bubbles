# Bubbles & Sun — website

Static one-page site for **Bubbles & Sun**, a laundromat + tanning salon at
279 Main St, Hudson Falls, NY. Sister rental business: TNT Rentals.

## Files
- `index.html` — the website (self-contained: HTML + CSS + JS in one file).
- `brand-assets.html` — open in a browser to download the Facebook cover, logo, and icon PNGs.
- `assets/generated/` — cartoon brand images (sun + pink bubble, the pink building, etc.).
- `.nojekyll` — tells GitHub Pages to serve the files as-is.
- `CNAME` — custom domain for GitHub Pages (`bubbles-and-sun.com`).

## Publishing on GitHub Pages
1. Push this folder to the repo (it must contain `index.html` at the root).
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)**. Save.
4. The site goes live at `https://bubbles-and-sun.com/` (fallback: `https://<user>.github.io/Bubbles/`).

## Custom domain (bubbles-and-sun.com)
DNS records at the domain registrar:
- Four `A` records on the apex (`@`): `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- One `CNAME` record: `www` → `akai127.github.io`

Then on GitHub: **Settings → Pages → Custom domain** should show `bubbles-and-sun.com`
(set automatically by the `CNAME` file). Tick **Enforce HTTPS** once the
certificate is issued (can take up to an hour after DNS propagates).

## Editing
Open `index.html` in any text editor. Hours, phone, address, and specials are
plain text near the top of the `<body>`. No build step — just edit and re-push.
