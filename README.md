# Soroi Larsens Camp: Guest Information

Single static site: `index.html` plus `qr-codes/` (review-link QR artwork) and `spa-menu/` (latest spa menu pages and PDF). Photos and video load live from the Media Portal's R2 bucket; fonts from Google Fonts. No build step.

## Deploy
Vercel: Add New, Project, import this repo, Framework Preset **Other**, Root Directory = repo root, Deploy.

## Updating content
Re-run `node scripts/generate-larsens-guest-info.js` in the main Graphic Designer project (content in `scripts/larsens-guest-info/content.js`, photo picks in `picks.js`), copy the refreshed `index.html`, `qr-codes/` and `spa-menu/` here, commit and push.
