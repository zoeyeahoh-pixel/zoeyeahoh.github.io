# Zoe Yang — small worlds

A one-page personal site: translator, writer, photographer, game maker.
Built with plain HTML, CSS and JavaScript — no framework, no build step.

## Files

- `index.html` — the whole site (styles and scripts inline)
- `assets/` — images, fonts, social preview
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy

The site is published from the `main` branch, root folder, at
<https://zoeyeahoh-pixel.github.io/zoeyeahoh.github.io/>.

## Local preview

```bash
python3 -m http.server 8000
# open http://127.0.0.1:8000/
```

`zoe-portfolio-standalone.html` (not deployed) is a single-file build with
fonts and images inlined, for offline viewing or sharing.
