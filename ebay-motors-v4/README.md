# eBay Motors Template v4 — Motion Mix

Single-file template (inline CSS in the head, no external stylesheet — so no CDN pin to update).

Adapted 21 Oct 2026 from the Car Parts Centre "azTpl" layout Waleed supplied (seller johnyboy-1, via 3D Sellers): navy top bar, logo header with red rule, scrolling marquee, two-column gallery + title/price/specs grid, navy description bar, GB reg-plate compatibility box, CSS-only Delivery/Returns/Payments/About tabs, dark footer.

## Branding
- Logo: Motion Mix triple-pill lockup (Waleed's upload, byte-identical to `~/workspace/motion-mix/pill-logo/motion-mix-logo-transparent.png`), hosted on Google Drive (folder "3S ONLINE eBay template images", shared anyone-with-link):
  `https://lh3.googleusercontent.com/d/1HmFdTo9_Oeyvq6jwNEBYuH24M3tvJJfr`
- Colours sampled from the logo: navy `#000A3D` / mid navy `#001E59`, red `#E60023`, blue `#0068FB`. Page background `#eaedf1` (from the reference), white card, max-width 1200px.

## Deliberately NOT copied from the reference
- Their seller links/logos (johnyboy-1, Car Parts Centre, imgpx), ad-lister / 3D Sellers wrappers and external CSS, hidden mobile-description block, Word mso table markup.
- Their policies: 15% restocking charge, buyer-paid returns, DPD surcharge list. v4 tabs carry Waleed's terms instead (same-day dispatch before 1:30pm, free tracked UK delivery ~2 business days, 30-day returns, eBay managed payments).
- Their marquee's "authorised distributors of LUK / Brembo…" claim — replaced with generic Motion Mix lines.

## Product data
Hardcoded from live listing 880023055144: Apec Blue PD3005 rear brake pads, £11.97, OE refs 191615415A / 191615415D / 191698451A / 1H0615415, EAN 5028906056469, TRW system, 87×53×17 mm, ECE R90 tag 90R-02A01400/42123, "compatible with 2,971 vehicles" fitment note. Main gallery image is the listing's first eBay image.

Store links: 3sonline store home / feedback / contact; "Add to Favourites" uses sellerid `walna43`.

## Use
Paste the whole file into the Seller Hub description editor (HTML view). For a new product, change: title (head + h1), price, gallery image, specs table rows, description lines.
