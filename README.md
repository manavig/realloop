# RealLoop

Marketing site for RealLoop — a marketplace for credible human judgment on production AI. Live at https://realloop.in/

## Files
- `index.html` — the live production site (mirrors what's deployed at realloop.in)
- `screens/` — product screenshots embedded in the page (`use-case`, `insights`, `reliability`, `training-mobile`)
- `archive-dark-early.html` / `archive-light-early.html` — earlier design explorations, kept for reference

It's a single self-contained HTML file. External dependencies are Google Fonts (Space Grotesk, Instrument Sans, IBM Plex Mono) and the local screenshots in `screens/`. It also links out to the `marketplace.realloop.in` and `portal.realloop.in` subdomains.

## Hosting & deploys
- Custom domain `realloop.in`.
- **Note:** the live site had drifted significantly from this repo in the past, so confirm how the domain actually deploys before assuming a push here updates production. GitHub lists a Vercel URL (`bolna-call-auditing.vercel.app`) as the homepage.

## Editing
- **In the browser:** open `index.html` on GitHub → pencil icon → edit → **Commit changes**.
- **Locally:** clone, open `index.html` in a browser to preview, edit, commit, push.
