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

## Photos to add later
The design works without photos. When Gilba's images arrive, good spots are:
- Pigment section: Vertmax on a fairway or green
- Grow lights section: SeeGrow rig on a stadium pitch
- Sensors section: an Omne Turf box in the ground
- Case studies: before and after dam photos (Federal GC, Twin Creeks)

Put images in `assets/img/` and give each one width, height and descriptive alt text.

Every page already uses `assets/img/og-card.png` (1200 x 630, text only) as its social share image. Replace it with a photo-based card once photos arrive, keeping the same file name.

## Still to confirm
- Public email address (hidden on gilbasolutions.com, so not on this site yet)
- Opening hours (Monday to Friday, 8am to 5pm, taken from the agronomy services page)
- A YouTube video to embed, if Gilba has one it wants featured
