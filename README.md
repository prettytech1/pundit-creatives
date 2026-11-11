# Pundit Creatives website

Static one-page site for Pundit Creatives, a videography and photography studio in Abuja.

- `index.html` — the whole site (styles and scripts inline)
- `assets/` — logo, favicon and social preview image
- `vercel.json` — clean URLs and long caching for assets

## Edit the Recent Work videos
In `index.html`, search for `var REELS` and change the YouTube `id`, `title` and `tag` for each card.

## WhatsApp number
Search for `WA_NUMBER` (international format, no `+`).

## Deploy
Push to GitHub, then import the repo on vercel.com. Framework preset: **Other**. No build command, output directory is the root.
