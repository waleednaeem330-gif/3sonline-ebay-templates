# 3S ONLINE — eBay Motors Template v3

Two-column motors template: NOVA-style hero header with CSS-only image
slider, left sidebar (store categories / why buy / trust badges),
centered title, hover gallery, green-labeled description rows, dark
fitment table, tab row, categories section, trust strip, dark footer
with SVG payment brand icons.

**Product:** Apec Blue rear brake pad set PD3005 (EAN 5028906056469).
All product data in `template.html` is **hardcoded** from eBay listing
880023055144 — title, specs, description, gallery images. There are no
merge fields: paste the HTML straight into the Seller Hub description
editor and everything shows.

## Files

- `template.html` — the listing description HTML (classes only).
  Product-specific: PD3005 data baked in.
- `css/style.css` — the whole design: hero, nav, sidebar, gallery,
  tables, tab row, categories, trust strip, footer, responsive
  breakpoints.

## Setup

The stylesheet is served live via jsDelivr CDN, pinned to an exact
commit so the CDN can never serve a stale copy:
`https://cdn.jsdelivr.net/gh/waleednaeem330-gif/3sonline-ebay-templates@<commit>/ebay-motors-v3/css/style.css`

If you edit `style.css`, push it, then update the commit SHA in the
`<link>` tag in `template.html` to the new commit and push that too.

## Notes

- To reuse this design for another product, duplicate the folder and
  swap the hardcoded product data (title, specs, images) in
  `template.html`.
- If the stylesheet ever fails to load, the listing degrades gracefully:
  tab panels show open and the first gallery image stays visible.
- eBay policy: static HTML + CSS only, no active content, HTTPS URLs.
  This template contains no JavaScript, forms, or iframes.
