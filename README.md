# Magic Comb Ltd — studio site

A single-page site for MAGIC COMB LTD, an independent game studio. One self-contained
`index.html`: no build step, no dependencies, no framework. Open the file in a browser
or drop it on any static host.

## Sections

- **Hero** — studio name, positioning line and a controller illustration (inline SVG)
- **Games** — three empty cards, ready for real titles
- **Studio** — six service blocks (original titles, co-development, engine work, live ops, release, playtesting)
- **How we build** — five production stages, concept through live ops
- **Platforms** — table of platforms and engines
- **FAQ** — questions from publishers and press

## Still to fill in

- The three game cards: key art, title, status, description, platforms
- The frame-rate and lead-time columns in the platforms table (currently `—`)
- Contact details and a footer, if the site needs them (both were removed)

## Design

- Fonts: Bricolage Grotesque (display) and IBM Plex Sans (body), loaded from Google Fonts
- Colors are CSS custom properties on `:root`, with a full dark theme that follows
  `prefers-color-scheme` and an explicit `data-theme` override
- Responsive down to roughly 380px wide; respects `prefers-reduced-motion`

## Local preview

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.
