repo: 911duplessis/PrimeTurf
branch: main
path: .

Secondary (Wix Velo logic/SEO): 911duplessis/PrimeTurf-Wix @ main, path src

## Last sync
date: 2026-09-17T13:40:00Z

### Updated in this project
- Reoriented to the real search demand (Cape Town + cost). New `Artificial Grass Cost.dc.html`: Gauteng R200-R600+/m2 and Western Cape R350-R850+/m2 bands side by side, three worked examples, six price drivers, an explicit inclusions list, and FAQPage schema covering the five highest-volume cost queries. Linked from the nav and footer of all 27 pages.
- Cape Town page (566 impressions / 0 clicks at position 33.9) retitled "Artificial Grass Cape Town - Prices From R350/m2" with a price-led meta description, plus a cost band section and natural "synthetic grass / fake grass" variants in body copy.
- Western Cape page retitled for the Winelands and Franschhoek queries that already show impressions; cost band added.
- Dual-region framing restored where it is true (Gauteng and the Western Cape) in hero copy, footers and the About standfirst.
- Email confirmed as leon@primeturf.co.za throughout; social@ not used anywhere.
- SEO + authenticity overhaul across 26 pages: unique title/description/canonical/OG/Twitter per page, LocalBusiness + BreadcrumbList on every page, FAQPage + Service on Home. No AggregateRating or Review schema anywhere (no verifiable review data exists).
- Removed all fabricated social proof: the "5-Star Google Rated" tile, the "48h typical install" metric, "17 suburbs served", "Gauteng's Premier Turf Specialist", "HOA and ARC Approved", and eleven invented project/customer locations (Sandhurst, Bryanston, Waterkloof, Fourways, Silver Lakes, Steyn City, Morningside, Mooikloof, Atlantic Seaboard, Lonehill, Garsfontein captions).
- Portfolio and Home galleries rebuilt from owner-supplied photographs only; unverified repo renders removed from both. New `Before and After.dc.html` (data-driven, scalable, neutral captions, optional location/detail fields that render only when filled).
- Facebook section added to Home, Portfolio and Before & After, linking the real page, with social graphics explicitly labelled as marketing artwork rather than project photography.
- Warranty claim corrected sitewide to "from 5 years" (Deco is 5yr per the real product cards).
- Added `sitemap.xml` (26 clean slugs) and `robots.txt`.
- Placed 131 real project photos from PrimeTurf `images/` (gallery-*, before/after, service-*, image(17) hero) into every image slot across all 25 pages; `image-slot.js` placeholders are gone.
- Grounded layout in the real `index.html` markup: forest top strip (water-restriction notice + pulse dot + WhatsApp chip), gold scrolling marquee, real hero (gold rule eyebrow "Precision Crafted. Luxury Installed.", "Elevate Your Outdoor Lifestyle." at weight 300, italic serif subhead, gold / green-WhatsApp / outline CTA trio) and the 6yr / 0L / 48h / 5-Star trust strip. Display type corrected to weight 300.
- Built `Artificial Grass Western Cape.dc.html` from its Velo module (10 real suburbs, 3 real FAQs, R350-R850/m2 regional band) and pointed the Service Areas card at it.
- Corrected the area count from "seventeen" to sixteen service areas across all pages.
- Adopted the canonical PrimeTurf brand system from `index.html` and the 14 `page-*.html` location pages: Deep Forest `#0B3D2E` / `#14543E`, Harvest Gold `#C9A44A` / `#E8C96E` / `#8A6B20`, near-black `#070E09`, Warm Ivory `#FAF8F2`, Cream `#F5F0E8`, muted `#7A7670` — replacing the placeholder palette across all 24 pages.
- Typography switched to the real stack: Cormorant Garamond (display) + Montserrat (body), with Cinzel loaded for the logo lockup.
- Official logo assets copied in: `pt-logo-full-light.svg` in every header, a plate-free gold `pt-logo-footer.svg` in every footer. Replaced the interim gold-ified PNGs.
- 13 location pages rebuilt on verbatim copy from the PrimeTurf-Wix Velo modules (hero subtitle, hero description, intro title/body, suburb lists, FAQs, CTA text) — replacing inferred text.

## Screen map
| Screen | Built from |
| --- | --- |
| Home.dc.html | PrimeTurf-Wix src/pages/Home.bqvuq.js + PrimeTurf index.html (brand system) |
| About.dc.html | PrimeTurf CLAUDE.md positioning, primeturf.co.za copy |
| Products.dc.html | primeturf.co.za/services-5 product catalogue |
| Portfolio.dc.html | PrimeTurf images/gallery-*.jpg — awaiting photo placement |
| Service Areas.dc.html | PrimeTurf-Wix src/pages/Service Areas.tdhd8.js |
| Get a Quote.dc.html | PrimeTurf-Wix src/pages/Get a Quote.evnw7.js; rates still placeholders |
| Contact.dc.html | PrimeTurf-Wix src/pages/Contact.m80pg.js, src/public/siteConfig.js |
| Artificial Grass Sandton / Johannesburg / Cape Town .dc.html | PrimeTurf-Wix per-page Velo modules |
| Artificial Grass Pretoria East, Silver Lakes, Mooikloof, Waterkloof, Faerie Glen, Garsfontein, Moreleta Park, Lynnwood, Centurion, Midrand, Hyde Park, Boksburg, Edenvale | corresponding PrimeTurf-Wix src/pages/*.js modules (verbatim copy) |
| Artificial Grass Western Cape.dc.html | PrimeTurf-Wix src/pages/Artificial Grass Western Cape.nz9gr.js (verbatim) |
| Artificial Grass Cost.dc.html | New - built from the Search Console cost-query cluster + the real per-m2 bands in the Velo pricing copy |
| Artificial Turf Gauteng.dc.html | PrimeTurf-Wix src/pages/Artificial Turf Gauteng.jhk27.js |

## Search Console findings (2026-09-17 export, 90 days)
- Demand is Cape Town + pricing, NOT Gauteng: "artificial grass cape town" 120 impressions, "synthetic grass cape town" 37, "fake grass cape town" 16, plus a long tail of cost queries. Gauteng queries are marginal ("artificial grass johannesburg" 2, "artificial grass randburg" 2).
- `/post/how-much-does-artificial-grass-cost-per-m-in-south-africa-2026` is the biggest asset: 1,055 impressions, position 14.8, 9 clicks.
- `/artificial-grass-cape-town.html` has 566 impressions and ZERO clicks at position 33.9.
- Duplicate page sets live side by side: old `.html` pages (`/page-sandton.html`, `/artificial-grass-johannesburg.html`) rank and get clicks while the new clean slugs (`/artificial-grass-sandton`, `/service-areas`) are "Crawled - currently not indexed" (13 URLs). Cannibalisation.
- Duplicate About: `/about-us` AND `/about-6` both indexed and both taking clicks. Duplicate Quote: `/quote-calculator.html`, `/quote/`, `/quote`.
- 11 x 404: trailing-slash variants (`/artificial-grass-sandton/`, `/artificial-grass-midrand/`, `/artificial-grass-centurion/`, `/artificial-grass-pretoria-east/`, `/artificial-grass-fourways/`), `/blog/artificial-grass-vs-natural-lawn-gauteng/`, `/blog/how-to-maintain-artificial-grass-south-africa/`, `/residential-artificial-grass-gauteng/`, `/school-playground-artificial-grass/`, `/privacy-policy/`, `/terms-of-service/`.
- 4 x "Blocked due to other 4xx": `/artificial-grass-johannesburg.html`, `/page-houghton.html`, `/page-pretoria-east.html`, non-www Cape Town.
- `/terms-of-service.html` is noindex; privacy policy 404s. Both needed before publishing.
- http:// and non-www variants indexed as "Page with redirect" — confirm one canonical host.

## Sync history
- 2026-09-17T09:40:00Z - real product tiles + catalogue tweaks; mobile nav drawer (nav-drawer.js).
- 2026-09-16T21:35:00Z - adopted the canonical brand system, logo, and verbatim location copy.
- 2026-09-16T12:40:00Z - built out all 17 location pages, About, nearby-area cross-links (before the PrimeTurf design repo was known).
- 2026-09-16T12:10:00Z - removed fabricated proof; Product Catalogue rebuilt on the real range.
- 2026-09-16T11:56:00Z - initial design of seven screens from the Velo modules.

## Notes
- Two repos: `PrimeTurf` holds the real design (HTML/CSS, brand tokens, logo assets, project photos); `PrimeTurf-Wix` holds Velo logic, SEO schemas and page copy. Design questions resolve against the former, copy against the latter.
- Resolved brand facts (per PrimeTurf CLAUDE.md): 6-year warranty (NOT 8), leon@primeturf.co.za, 076 804 8868, positioning "Luxury Artificial Turf Specialists, Serving Gauteng & Western Cape".
- Still to do: wire estimator rates from the live PricingSettings / TurfSpecs values (currently placeholders).
- `src/pages/Artificial Grass Roodepoort.xtajx.js` exists upstream but is an empty stub (console.info only) with no copy, so no Roodepoort page was built and it is not listed as a service area. Add copy upstream and it can be generated.
- Real-site facts not yet reconciled: index.html's strip uses social@primeturf.co.za while the Velo siteConfig uses leon@primeturf.co.za (leon@ kept); index.html cites "9 premium SKUs" against the 7-product catalogue on primeturf.co.za.
- Western Cape is a REGIONAL page only — per CLAUDE.md, do not invent suburbs, branches, offices, projects or testimonials for it.
- No design system is attached to this project (the bound project is empty); the brand system above is the reference.
