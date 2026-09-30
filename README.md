# Raina Ghasha Haris — Portfolio Website (v4, Content Creator / Social Media Specialist / KOL)

Static one-page portfolio (HTML/CSS/vanilla JS, no build step, no dependencies). This version is a
**narrative variant of v3** — same validated data and design system, reframed toward **Content
Creator, Social Media Specialist and KOL** positioning. See `CONTENT-DECISIONS-v4.md` for exactly
what changed vs. v3, and `CONTENT-DECISIONS-v3.md` for the full data-source audit trail (GPA,
email, DISNAKER claims, TVC Cimory / Film Sariwangi role sourcing, etc.).

## Structure

```
index.html
assets/
  css/style.css     design tokens + all component styles (unchanged from v3/v2)
  js/main.js        nav scrollspy, mobile menu, scroll-reveal, lightbox, progress bar (unchanged)
  icons/favicon.svg
  img/               all photos, certificates and poster crops, optimized as JPG
```

## Deploy

Fully static site — upload the whole folder as-is to any static host:

- **Netlify / Vercel**: drag-and-drop the folder (or connect a repo) — no build command needed,
  output directory is `/`.
- **GitHub Pages**: push this folder to a repo and enable Pages on the branch/`root`.
- **Any shared/cPanel hosting**: upload the contents of this folder into `public_html/`.

No environment variables, no server, no database.

## Editing content

All copy lives directly in `index.html`. Colors and fonts are defined as CSS custom
properties at the top of `assets/css/style.css` under `:root` — change `--bg-deep`,
`--accent`, `--green` etc. to re-theme the whole site.

## Design system (unchanged)

- Dominant background: azure navy `#123B63`
- Accent: gold/tan `#C5A46D`
- Secondary accent: deep green `#1B2E28`
- Display font: Fraunces · Body: Plus Jakarta Sans · Data/labels: IBM Plex Mono

## What's different from v3 — see `CONTENT-DECISIONS-v4.md`

Positioning reframed to Content Creator / Social Media Specialist / KOL: hero tagline, marquee,
About, DISNAKER internship title & bullets, Competencies groups, and section leads updated. No
facts, certificates, links or images were changed or added — this is a narrative/framing pass on
top of the same validated v3 content. The same open item from v3 still applies: **the contact
email (`derainaharis@gmail.com`) needs Raina's final confirmation** before publishing (see
`CONTENT-DECISIONS-v3.md`).
