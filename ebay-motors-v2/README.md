# 3S ONLINE — eBay Motors Template v2

Professional eBay Motors listing template with pure-CSS interactivity
(no JavaScript): hover image gallery + accordion tabs. Styling lives in
`css/style.css`, loaded via a `<link>` tag — the same architecture the
big template sellers use.

## Files

- `template.html` — the listing description HTML (classes only, no inline
  styling except the body background). Uses MIP merge fields
  (`${PRODUCT.Title}`, `${PRODUCT.Description}`,
  `${PRODUCT.CustomFields ...}`) so feed listings auto-fill.
- `css/style.css` — the whole design: layout, hover gallery, accordion
  tabs, responsive breakpoints.

## Setup

1. Push this folder to your GitHub repo. (Done: https://github.com/waleednaeem330-gif/3sonline-ebay-templates)
2. The live stylesheet is served via jsDelivr CDN (works immediately,
   correct content-type, no Pages setup needed):
   `https://cdn.jsdelivr.net/gh/waleednaeem330-gif/3sonline-ebay-templates@main/ebay-motors-v2/css/style.css`
   (Alternative: enable GitHub Pages in repo Settings > Pages and use
   `https://waleednaeem330-gif.github.io/3sonline-ebay-templates/ebay-motors-v2/css/style.css`.)
3. In `template.html`, the stylesheet link already points at the jsDelivr URL.
4. For MIP feed listings: upload `template.html` via MIP GUI >
   Description Templates (or SFTP `/store/lookup/template`) **before**
   the feed, then set `TemplateName=template.html` in each feed row and
   fill `CustomFields` (pipe-delimited, no spaces — see the comment block
   at the top of `template.html` for the full key list).

## Notes

- Merge fields only auto-fill through the MIP feed workflow. Pasted
  manually into Seller Hub, `${...}` codes show as literal text.
- If the stylesheet ever fails to load, the listing degrades gracefully:
  accordion panels show open and the first gallery image stays visible.
- eBay policy: static HTML + CSS only, no active content, HTTPS URLs.
  This template contains no JavaScript, forms, or iframes.
