# Robina Mushtaq — Portfolio

Personal portfolio site for Robina Mushtaq, real estate consultant in Dubai.
Plain HTML, CSS and JavaScript — no build step, no dependencies.

## Run locally

```bash
npx serve .        # or: python3 -m http.server 3000
```

Then open http://localhost:3000.

## Deploy

Import this repository in Vercel (Framework preset: **Other**, no build command, output directory `.`). Every push to `main` redeploys.

## Edit content

- Text: `index.html`
- Colours and fonts: the `:root` variables at the top of `styles.css`
- Photos: see below

## Photos

Create an `images` folder and drop Robina's photos here with these exact file names:

| File | Used in |
|---|---|
| `robina-hero.webp` | Hero portrait (already added; replace with a higher-resolution original, ~1600×1280) |
| `robina-portrait.jpg` | Arched portrait in the About section (portrait ~1000×1250) |
| `robina-podcast.jpg` | "The Next Address" podcast feature (landscape ~1500×1000) |
| `robina-avatar.jpg` | Small round photo in the Contact section (square ~300×300) |

Until a file is added, the site shows a neutral placeholder in its place.
