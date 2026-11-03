# Aditya Kumar — Personal Website

Static portfolio site, published with GitHub Pages. No build step: plain HTML + CSS + JS.

## Contents

- `index.html` — the site (Intro, About, Experience, Research, Projects, Toolbox, Contact)
- `assets/css/style.css`, `assets/js/main.js` — styling and interaction
- `assets/` — IEEE paper PDF, portrait and about photos
- `variants/` — earlier design explorations (harbor, ledger, arcade, fusion)
- `PRODUCT.md`, `.impeccable/` — product notes and design-process records

Content: resume + GitHub [`@adityatheperson`](https://github.com/adityatheperson),
IEEE ICCE 2025 paper PDF, user-supplied photos.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## How it's published

Repo: `adityatheperson/personal-website`, branch `main`, root `/`.
GitHub → Settings → Pages → Deploy from branch → `main` / `/ (root)`.
Live at `https://adityatheperson.github.io/personal-website/`.
