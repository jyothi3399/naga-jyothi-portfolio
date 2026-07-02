# Kommula Naga Jyothi — Portfolio

Single-file portfolio (`index.html`) — no build step needed. Dark theme with an
"aperture/shutter" signature motif (nod to the photobooth project), tab
navigation (Home / About / Skills / Experience / Projects / Education /
Contact), hash-based URLs so browser back/forward works, and a copy-to-clipboard
on the email/phone cards.

## Publish on GitHub Pages (free, 2 minutes)

1. Create a new repo on GitHub, e.g. `naga-jyothi-portfolio`.
2. Upload `index.html` to the repo (drag-and-drop on the GitHub website works,
   or `git add index.html && git commit -m "portfolio" && git push`).
3. In the repo: **Settings → Pages → Source → Deploy from branch → main → / (root) → Save**.
4. After ~1 minute your site is live at:
   `https://<your-github-username>.github.io/naga-jyothi-portfolio/`

## Before you publish — 2 things to fill in

- In `index.html`, search for `add-your-github-url` (Contact section) and
  replace the link/text with your real GitHub profile URL.
- Optional: add a LinkedIn card the same way you see the GitHub one, once you
  have a public LinkedIn URL.

## Customizing later

- Colors/fonts live at the top of the `<style>` block under `:root` — change
  `--accent` (amber) or `--accent-2` (teal) to reshuffle the whole palette.
- Each resume section is its own `<section class="panel" id="panel-...">` —
  easy to find and edit by section name.


