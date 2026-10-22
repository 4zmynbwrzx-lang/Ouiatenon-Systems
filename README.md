# Ouiatenon-Systems

Company website for Ouiatenon Systems LLC, deployed on Cloudflare Workers (static assets).

## Layout

- `wrangler.jsonc` — Worker config; serves everything in `public/`
- `public/index.html` — home page
- `public/styles.css` — styles
- `public/404.html`, `public/favicon.svg`

## Deploy

Pushing to `main` triggers Cloudflare's Git build, which runs `npx wrangler deploy`. No build step is needed.

Local preview: `npx wrangler dev`
