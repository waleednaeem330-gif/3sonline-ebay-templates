# 3S ONLINE — eBay Motors Template v3

Two-column motors template matching a teal design reference: hero
banner, pill navigation, left sidebar (store categories / why buy /
promo boxes), centered title, hover gallery, green-labeled description
rows, dark fitment table, tab row, dark footer. All copy is original
3S ONLINE text — only the layout structure follows the reference.

## Files

- `template.html` — the listing description HTML (classes only). Uses MIP
  merge fields (`${PRODUCT.Title}`, `${PRODUCT.Description}`,
  `${PRODUCT.CustomFields ...}`) so feed listings auto-fill.
- `css/style.css` — the whole design: hero, nav, sidebar, gallery, tables,
  tab row, footer, responsive breakpoints.

## Setup

The stylesheet is served live via jsDelivr CDN (works immediately,
correct content-type, no Pages setup needed):
`https://cdn.jsdelivr.net/gh/waleednaeem330-gif/3sonline-ebay-templates@main/ebay-motors-v3/css/style.css`

For MIP feed listings: upload `template.html` via MIP GUI > Description
Templates (or SFTP `/store/lookup/template`) **before** the feed, then set
`TemplateName=template.html` in each feed row and fill `CustomFields`
(pipe-delimited, no spaces — see the comment block at the top of
`template.html` for the full key list).

## Notes

- Merge fields only auto-fill through the MIP feed workflow. Pasted
  manually into Seller Hub, `${...}` codes show as literal text.
- If the stylesheet ever fails to load, the listing degrades gracefully:
  tab panels show open and the first gallery image stays visible.
- eBay policy: static HTML + CSS only, no active content, HTTPS URLs.
  This template contains no JavaScript, forms, or iframes.
