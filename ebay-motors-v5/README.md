# eBay Motors Template v5 — Motion Mix (flagship)

Single-file template (inline CSS, no external stylesheet, no CDN pin).

Original design built 21 Oct 2026 at Waleed's request ("recreate the template with your creativity") around the Motion Mix triple-pill identity: the three pills become the design language — tricolour speed bar under the header and above the copyright bar, navy gradient hero with giant translucent CSS pill shapes behind the photo, gradient headline text, gradient icon chips, and a red-to-orange marquee and CTA buttons.

## Sections
Utility bar (UK Seller / 1:30pm dispatch / free tracked delivery / 30-day returns) → logo header with store nav + "Shop All Parts" CTA → hero ("Premium Braking. Perfect Fit.", brake-disc photo with ECE R90 + Fitment Checked chips, Check Your Fitment anchor button) → marquee → product grid: click-to-switch CSS gallery (3 photos, 4:5 portrait frame, active thumbnail outlined red) + breadcrumb, title, trust chips, price box (£11.97 with same-day dispatch panel), quick-spec tiles, striped spec table, Ask / Favourites buttons → 4 feature cards (OE quality, fitment checked, same-day dispatch, 30-day returns) → description panel (the "In The Box" card was removed 21 Oct at Waleed's request) → fitment table + GB reg-plate compatibility box → 6 category cards (placeholder `#` links, as in v3) → pill tabs (Delivery / Returns / Payments / About) → dark footer with pills icon, quick links, payment chips (Visa / Mastercard / PayPal / Amex / Discover).

## Resources (all Drive folder "3S ONLINE eBay template images", anyone-with-link)
- Header logo: `1HmFdTo9_Oeyvq6jwNEBYuH24M3tvJJfr` (motion-mix-logo.png)
- Footer pills icon: `1RrEmFr0u-Vnc3lQzk0ZL9YLRpyuEs4hR` (motion-mix-icon.png)
- Hero brake discs: `1BU-KSir65BD3wlC0WNk1Zwa0v9YJ_0X1`
- Store banner (added 21 Oct 2026 at Waleed's request): `1Y2WnIR1KegIempYbAWPk3xkJgUkeZgmn` (mm-banner-pile-sky.jpg — the sky-background "Quality Car Parts" pile banner) shown full-width between the header and the hero, linked to the store home.
- Gallery: the PD3005 listing's 3 eBay images (i.ebayimg.com)

## Data & policies
Hardcoded PD3005 data from listing 880023055144 (£11.97, EAN 5028906056469, TRW, 87×53×17 mm, ECE R90 90R-02A01400/42123, 2,971-vehicle fitment note, 25-month/25,000-mile guarantee). Tabs/footer carry Waleed's terms only. Store links: 3sonline; favourites sellerid `walna43`.

## Verified
Rendered desktop (1280px) and mobile (390px) via headless Chromium using a local-assets preview copy (`preview-local.html`, screenshots alongside) — layout, gallery switching state, tabs, reg plate and footer all confirmed. The live file references the remote URLs above, each verified HTTP 200.

## Use
Paste the whole file into the Seller Hub description editor (HTML view). For a new product, change: title (head + h1), price, gallery image URLs (3 slides + 3 thumbs), quick tiles, spec table rows, fitment rows.
