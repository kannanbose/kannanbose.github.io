# Kannan Bose — Professional Dossier

Personal portfolio site for **Kannan Bose** — ESG, Sustainability, EHS and
Ethics & Compliance leadership across 28 manufacturing sites.

**Live:** https://kannanbose.github.io

## Contents

| File | Purpose |
|---|---|
| `index.html` | The entire site — self-contained, no build step, no dependencies |
| `Kannan-Bose-CV.pdf` | Downloadable CV |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Notes

`index.html` is fully standalone: all CSS, JavaScript, SVG artwork and the
portrait (embedded as a base64 PNG) live inside the single file. There are no
external requests, so it renders identically offline and on any host.

The animated background (drifting particles and the rotating wireframe globe
behind the Contact section) is hand-written Canvas 2D — no libraries.
Everything respects `prefers-reduced-motion`.

## Editing

Open `index.html` in any editor. Content sits in plain HTML sections
(`#home`, `#about`, `#impact`, `#work`, `#skills`, `#career`, `#education`,
`#contact`); the design tokens are the CSS custom properties in `:root`.
