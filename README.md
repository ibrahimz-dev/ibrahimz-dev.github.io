# Ibrahim Zaryouh — Portfolio

Personal portfolio site for **Ibrahim Zaryouh**, served with GitHub Pages from this repo.

- **Live:** https://ibrahimz-dev.github.io/
- **Stack:** semantic HTML, hand-written CSS, vanilla JS — no frameworks, no trackers.
- **Identity:** IZ emblem in `assets/logo.png` (futuristic dark-tech: near-black/navy, electric-blue-to-cyan).

## Structure

| File | Purpose |
|---|---|
| `index.html` | Navbar, hero, projects, about, skills, education, contact |
| `styles.css` | Palette `#05070B #0B1220 #287BFF #11C8F4 #F4F7FC #8493AA`, Space Grotesk / Inter / JetBrains Mono |
| `script.js` | Scroll reveals (reduced-motion aware), footer year |
| `assets/logo.png` | IZ monogram emblem, favicon + hero visual |

## Local preview

```bash
# any static server, e.g.
npx serve .
# or
python -m http.server 8000
```

## Deployment

Push to `main` — GitHub Pages (`legacy`, `main:/`) rebuilds https://ibrahimz-dev.github.io/ automatically.
