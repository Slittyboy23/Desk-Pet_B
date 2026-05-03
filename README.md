# Desk Pet — by Brooklyn

Tiny handmade pets in their own little world.
Pick your animal. Pick your base. Take them home.

## What's here
- `index.html` — Home page (hero, 3-step process, product gallery, story strip)
- `about.html` — About Brooklyn (photo, bio, fun facts)
- `styles.css` — Full theme (teal / purple / pink on warm cream)
- `images/` — Drop product photos here (`product1.jpg` … `product4.jpg`, `brooklyn.jpg`)

## Local preview
Just open `index.html` in your browser. No build step.

Or run a tiny local server (so navigation feels real):
```
cd desk-pet-brooklyn
python3 -m http.server 8000
```
Then visit http://localhost:8000

## Deploying
Any static host works for free:
- **GitHub Pages** — Settings → Pages → deploy from `main` branch
- **Netlify** — drag the folder onto netlify.com
- **Vercel** — `vercel` CLI in this folder

## Editing
- Bio copy lives in `about.html` — replace the `[ ... ]` placeholder blocks
- Product names live in `index.html` (`No. 01`, `No. 02`, etc.)
- Brand colors are CSS variables at the top of `styles.css` (`--teal`, `--purple`, `--pink`)
