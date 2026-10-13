# Sterling Pump Systems — review build

Working build prepared by The Quill Company. Not the live site.

**Review only.** `robots.txt` blocks all crawlers and every page carries a `noindex` tag,
so this copy will not be indexed and cannot compete with sterlingpumpsystems.com in search.
Leave both in place for as long as this repo is public.

## What is here

- `index.html` — homepage
- `catalog.html` — 48-unit catalog with filters
- `unit-*.html` — three finished unit pages
- `img/` — photography from Sterling's own eBay listings

## Sources

- Copy, phone numbers, address and hours: sterlingpumpsystems.com, fetched 13 Oct 2026
- Catalog and photography: Sterling's eBay store, captured 03 Sep 2026 (48 of ~100 listings)

Nothing on these pages is asserted beyond those two sources.

## Publishing to GitHub Pages

    git init
    git add -A
    git commit -m "Sterling review build"
    git branch -M main
    git remote add origin https://github.com/<you>/<repo>.git
    git push -u origin main

Then in the repo: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.

The URL appears on that page within a minute or two and looks like
`https://<you>.github.io/<repo>/`.
