# Ancrage

Marketing site for Ancrage — an AI-native private equity firm.

## Structure

Single-page static site. All HTML/CSS lives in `index.html`.

- `index.html` — the site
- `vercel.json` — Vercel static config
- `ancrage-website.html` — original source (kept as a backup; safe to delete)

## Deploy

The repo is wired for Vercel. Importing it from GitHub will deploy automatically — no build step, no framework preset needed (Vercel detects "Other" / static).

Local preview:

```bash
# any static file server works, e.g.
npx serve .
```
