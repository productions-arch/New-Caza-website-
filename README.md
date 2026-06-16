# CAZA — Film & Television Studio

The website for [caza.productions](https://caza.productions), a film and television
studio telling the best stories and restoring the moving image to its original
dominance.

## Design

Built on the **Structured** design system — a "Renaissance gallery on putty paper"
aesthetic. Warm putty-beige canvas, stark black accents, a monumental serif
wordmark, and alternating light / dark full-bleed sections. Entirely flat: no
gradients between sections, no shadows, no saturated color.

- **Display serif:** Davinci (substituted with Playfair Display)
- **Utility grotesk:** Helvetica Now (substituted with Inter)
- **Canvas:** Putty `#c4c3b6` · **Ink:** `#000000`

## Structure

A single-page static site — no build step required.

| File | Purpose |
|------|---------|
| `index.html` | Page markup and content |
| `styles.css` | Design tokens and all styling |

## Running locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Sections

1. **Hero** — eyebrow, headline, stat row, CTA, and the monumental `CAZA` wordmark
2. **Studio** — the manifesto
3. **Slate** — floating notched product card over a canvas atmosphere
4. **What we make** — dark feature with circular vignettes (Film · TV · Originals)
5. **How we work** — three principles
6. **Contact** — bring us a story
