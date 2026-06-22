# Personal Projects Showcase

Siya Yan's personal index — three standalone design variants, no build step. Open any HTML file in a browser.

| File | Design |
|------|--------|
| `index.html` | **Spatial Hub** (flagship) — 3D parallax hero with 4 sector cards + editorial body |
| `spatial.html` | **Spatial** — dark HUD node-field with 9 floating project nodes |
| `editorial.html` | **Home** — editorial scrolling index with Ink / Carbon / Sand theme switcher |

## Features
- Mouse-driven 3D parallax, radar sweep, floating-node animation
- Live theme switching (mood chips)
- Live project thumbnails via `image.thum.io`
- Embedded Claude artifact
- Live clock, marquee, grain overlay

## Local preview
Any static file server works, e.g.:

```bash
npx serve .
```

Then open `http://localhost:3000`.
