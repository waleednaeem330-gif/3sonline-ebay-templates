# eBay Motors Template v5 — Motion Mix (flagship)

Single-file template (inline CSS, no external stylesheet, no CDN pin).

Original design built 21 Oct 2026 at Waleed's request ("recreate the template with your creativity") around the Motion Mix triple-pill identity: the three pills become the design language — tricolour speed bar under the header and above the copyright bar, navy accents, gradient headline text, gradient icon chips, and a red-to-orange marquee and CTA buttons.

## Sections
Utility bar (UK Seller / 1:30pm dispatch / free tracked delivery / 30-day returns) → logo header with store nav + "Shop All Parts" CTA → banner slider (CSS-only autoplay crossfade, 3 Motion Mix banners at 5s each, added 21 Oct 2026; the original "Premium Braking" hero was removed the same day at Waleed's request) → marquee → product grid: click-to-switch CSS gallery (3 photos, 4:5 portrait frame, active thumbnail outlined red) + breadcrumb, title, trust chips, price box (£11.97 with same-day dispatch panel), quick-spec tiles, striped spec table, Ask / Favourites buttons → 4 feature cards (OE quality, fitment checked, same-day dispatch, 30-day returns) → description panel (the "In The Box" card was removed 21 Oct at Waleed's request) → fitment table + GB reg-plate compatibility box → 6 category cards (placeholder `#` links, as in v3) → pill tabs (Delivery / Returns / Payments / About) → dark footer with pills icon, quick links, payment chips (Visa / Mastercard / PayPal / Amex / Discover).

## Resources (all Drive folder "3S ONLINE eBay template images", anyone-with-link)
- Header logo: `1HmFdTo9_Oeyvq6jwNEBYuH24M3tvJJfr` (motion-mix-logo.png)
- Footer pills icon: `1RrEmFr0u-Vnc3lQzk0ZL9YLRpyuEs4hR` (motion-mix-icon.png)
- Slider banners (Drive, in play order): sky "Quality Car Parts" `1Y2WnIR1KegIempYbAWPk3xkJgUkeZgmn` / parts frame `1lkLdwd3Q5bhweOROEIgDDw4Rts1sz1x_` / complete bunch `1-nZO05mek_hHCGPVaGBsYSO1QqiWp53l` — each full-width, linked to the store home. (The hero brake-disc photo `1BU-KSir65BD3wlC0WNk1Zwa0v9YJ_0X1` is no longer used.)
- Gallery: the PD3005 listing's 3 eBay images (i.ebayimg.com)

## Data & policies
Hardcoded PD3005 data from listing 880023055144 (£11.97, EAN 5028906056469, TRW, 87×53×17 mm, ECE R90 90R-02A01400/42123, 2,971-vehicle fitment note, 25-month/25,000-mile guarantee). Tabs/footer carry Waleed's terms only. Store links: 3sonline; favourites sellerid `walna43`.

## Verified
Rendered desktop (1280px) and mobile (390px) via headless Chromium using a local-assets preview copy (`preview-local.html`, screenshots alongside) — layout, gallery switching state, tabs, reg plate and footer all confirmed. The live file references the remote URLs above, each verified HTTP 200. Slider autoplay verified numerically via Chrome DevTools (computed slide opacities 0,1,0 at ~6s and 0,0,1 at ~12s) plus screenshots.

## Use
Paste the whole file into the Seller Hub description editor (HTML view). For a new product, change: title (head + h1), price, gallery image URLs (3 slides + 3 thumbs), quick tiles, spec table rows, fitment rows.
