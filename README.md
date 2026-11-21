# Gilba Solutions: Cloudflare Pages site (turf products and water focus)

Static site for Cloudflare Pages. No build step: connect the repository in Cloudflare (Workers & Pages, then Pages, then "Connect to Git"), leave the build command blank and set the output directory to `/`.

**Planned address:** https://gilbasolutions.pages.dev/
If the Pages project gets a different name, change the address in the canonical tags, `sitemap.xml` and `robots.txt`.

## Pages
- `index.html`: home page (Vertmax pigments, SeeGrow grow lights, Omne Turf sensors, wetting agents, dam weeds and algae, about, contact)
- `case-studies/`: blog listing
- `case-studies/federal-golf-club-dam-clipper-herbicide/`
- `case-studies/twin-creeks-blue-green-algae-agri-tec/`
- `404.html`, `robots.txt`, `sitemap.xml`, `_headers`

## Images (from SEOBranding\public\images\Gilba, 21 Nov 2026)
- `gilba-solutions-logo-white.png` / `.webp`: header logo (white lettering for the dark header)
- `vertmax-duo-logo`, `stadium-pitch-turf`: pigment section
- `seegrow-logo`, `tls-led-400-grow-light-rig`: grow lights section
- `omne-turf-logo`: sensors section
- `product-*`: "More from the Gilba range" strip (names only, no claims)
- `golf-course-green`, `golf-course-fairway`: case studies, captioned as illustrative

Still worth adding later: real before/after dam photos from Federal GC and Twin Creeks, and an Omne Turf box installed on a site.

Every page already uses `assets/img/og-card.png` (1200 x 630, text only) as its social share image. Replace it with a photo-based card once photos arrive, keeping the same file name.

## Still to confirm
- Opening hours (Monday to Friday, 8am to 5pm, taken from the agronomy services page)
- A YouTube video to embed, if Gilba has one it wants featured
