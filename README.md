# Personal site

A single static page. No build step — just HTML + CSS.

## Files
- `index.html` — the page
- `assets/background.jpg` — your background portrait (replace this file)

## Set it up
1. Put your background photo at `assets/background.jpg` (any wide image works; it's used full-bleed with `background-size: cover`).
2. In `index.html`, edit the three links and the two social icons:
   - `Reflexive Codes`, `music`, `write` → replace `href="#"` with the real URLs.
   - Email icon → change `mailto:hello@example.com` to your address.
   - Instagram icon → change `https://instagram.com/` to your profile.

## Publish with GitHub Pages
1. Create a repo and upload the contents of this `site/` folder to its root
   (so `index.html` is at the top level).
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → branch `main`, folder `/root`.
3. Your site goes live at `https://<username>.github.io/<repo>/`.

## Fonts
The original uses "Arizona Text" (a licensed Dinamo typeface). This page falls
back to Google's **Newsreader** as a close serif. If you own the Arizona web
fonts, add an `@font-face` block in the `<style>` and it will be used
automatically (the CSS already lists it first in the font stack).
