# SimpleWeb — Georgian small-business website portfolio

Simple responsive one-page website for **SimpleWeb**, a web design service for small businesses in Georgia.

## Links
- Café demo: https://simpleuser0.github.io/Test_Cafe/
- Salon demo: https://simpleuser0.github.io/lumi-beauty-studio/
- Contact: https://www.instagram.com/simpleweb.ge/

Both example projects are **demos**, not real paid client projects.

## Technology
- Static HTML / CSS / vanilla JavaScript.
- No dependencies, build pipeline, database, account forms, or tracking.
- Google Fonts (DM Sans and Noto Sans Georgian) are optional; fallback fonts available.
- Page works with relative asset paths in root (`./styles.css`, `./script.js`, `./favicon.svg`).

## Development
Open `index.html` in a browser. For local testing, an HTTP server can be started with `python -m http.server 8000`.

## Deployment: Cloudflare Pages (suggested for business sites)
1. In Cloudflare, choose **Workers & Pages → Create → Pages → Connect to Git**.
2. Select GitHub repository `SimpleUSER0/SimpleWeb-Project`.
3. Choose production branch **main**.
4. Framework preset: **None**.
5. Build command: `exit 0` (or leave empty if allowed).
6. Build output directory: `/` or `.` (repository root).
7. Deploy. Pages will provide a `*.pages.dev` domain, with future updates triggered by GitHub commits.

**Why Cloudflare?** GitHub Pages policy explicitly disallows free-hosting sites primarily intended to run an online business or facilitate commercial transactions. The portfolio is intended to sell services, so use an appropriate commercial-friendly static host. The GitHub repository remains the source of truth.

## Business notes
- Starting price shown as **100 GEL**; domain registration/renewal is extra.
- Optional annual tech support **60 GEL**.
- Timeline **2–3 business days** for standard small sites after materials arrive; not a universal guarantee.
- No built-in CMS or booking system.
- Change the displayed prices and conditions if the offer evolves.

## Pre-launch checks
- Verify both external demo links.
- Verify the Instagram username is correct.
- Check desktop/mobile layouts, keyboard navigation, and FAQ.
- Connect a custom domain only when ready; register it in the business owner's name.
