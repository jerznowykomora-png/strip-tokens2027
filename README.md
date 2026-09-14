# Stripchat Token Guide

A static, accessibility-minded, safety-first educational site about evaluating Stripchat token promotions. It does not distribute hacks, mod APKs, generators, or unauthorized access tools.

## Local preview

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080/`. The site is pure HTML, CSS, and vanilla JavaScript. The table of contents is generated from each page's headings by `assets/script.js`.

## Pages

- `index.html` — overview
- `guide.html` — step-by-step safety guide
- `methods.html` — method comparison
- `updates.html` — promotions and outlook
- `sitemap.xml` and `robots.txt` — crawler essentials

GitHub Pages deployment is defined in `.github/workflows/pages.yml` and runs when the `main` branch is updated or manually dispatched.
