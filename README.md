# Graeme Steele — Executive Portfolio

A single-page executive portfolio site for Graeme Steele (Corporate Real Estate,
Workplace Leadership & Capital Programme Delivery).

Static site — no build step. Just `index.html`, `styles.css`, and `assets/`.

## Structure

- `index.html` — the page markup
- `styles.css` — all styling (design tokens, layout, responsive breakpoints)
- `assets/` — headshot and company logos

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Published via GitHub Pages from the `main` branch (root). Any push to `main`
updates the live site.
