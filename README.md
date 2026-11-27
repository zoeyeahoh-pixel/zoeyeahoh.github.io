# Zoe Yang — Welcome to my world

A one-page personal site built from the latest `zoe-portfolio` HTML: the
click-to-enter floating island, the oversized “Welcome to my world!” watermark,
three hotspots on the island, garden-plot project cards, and a small seasonal
fall layer that changes with the month.

## Files

- `index.html` — the whole site (styles and scripts inline)
- `assets/` — images, self-hosted fonts, social preview
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Seasons

The falling layer follows the local month:

| Months | Falling |
| --- | --- |
| Jan–Mar | green leaves |
| Apr–Jun | petals |
| Jul–Sep | yellow ginkgo leaves |
| Oct–Dec | snow |

Preview any season with `?season=spring`, `?season=summer`, `?season=autumn`
or `?season=winter`.

## Music

The BGM is `music/day-after-day.m4a` (audio extracted from `bgm.mp4`),
with its vinyl nameplate cover at `assets/bgm-cover.webp`.

## Local preview

```bash
python3 -m http.server 8000
# open http://127.0.0.1:8000/
```

`zoe-portfolio-standalone.html` (not deployed) is a single-file build with
fonts and images inlined, for offline viewing or sharing.
