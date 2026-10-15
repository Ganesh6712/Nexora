# NEXORA TechSprint 2K26 — Official Event Website

National-level technology & innovation championship · S-VYASA Deemed to be University, Global City campus, Bengaluru.
**Two days · Five challenges · One national stage.**

## What's inside

| File | Purpose |
|---|---|
| `index.html` | The entire website — a single self-contained file (all CSS, JS, fonts, map, photography and challenge artwork embedded as data URIs). No build step, no dependencies, no backend. |
| `og-image.jpg` | 1200×630 social share card (Open Graph / Twitter Card). |

## Page highlights

- Scroll-driven **India → Karnataka → Bengaluru → S-VYASA** map journey (inline SVG, official India map incl. J&K + Ladakh UTs)
- **The Arena** — five challenge cards with generated violet artwork backgrounds + hover previews
- Event journey (Day 1 / Day 2 tabs), prizes, passes, sponsors, FAQ
- Registration via Google Form; contacts via `tel:` / `mailto:` links
- Respects `prefers-reduced-motion`, mobile-responsive, performance mode for low-end devices

## Deploy

Static hosting only — upload this folder as-is.

- **Netlify:** drag this folder onto https://app.netlify.com/drop (site name `nexora-techsprint2k26` keeps the OG share tags valid), or import this repo via *Add new site → Import with Git* (publish directory: repo root).
- **Vercel / Cloudflare Pages / GitHub Pages:** point the project at this folder / repo root. No build command, no output directory beyond the root.

## Edit

Everything lives in `index.html`. Search for the section comments (`<!-- ARENA -->`, `<!-- JOURNEY -->`, `<!-- PRIZES -->`, …) to navigate. Registration form URL, contact details and sponsor names are plain text/attributes inside that file.

© 2026 NEXORA TechSprint. Campus photos: Gpkp / Wikimedia Commons · CC BY-SA 4.0.
