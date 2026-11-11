# Standalone portfolio draft — built 2026-11-10

Fallback to the Framer rebuild, which is blocked at Framer sign-in
("Verification failed. Please try again", twice in the cloud browser;
phone in-app browser unavailable at 2026-11-10 15:46 EST).
This site does not need Framer, Wix, or any sign-in to build.

## Contents
- `index.html` — home, Utah Wildfire Risk hero, cleaned intro (the live
  Wix intro was garbled: "government cliens" / "Emergency MaAward"),
  Jane Jacobs quote, links to Reports and Gallery.
- `gallery.html` — all 23 maps, in Wix lightbox order, from
  `assets/gallery/` (15 MB total, downloaded and verified 2026-11-10).
- `reports.html` — all 16 reports with links. The two link-less Wix
  reports are resolved from the Drive Report References folder:
  Longmont Rails-to-Trails and Clean Air Communities. The SLC bus
  routes piece is an ArcGIS StoryMap link, not a file.
- `style.css` — topography / mountains / forests direction from Luke:
  contour-line motif, deep forest green, warm stone, cream.

Source of truth: `../wix-inventory-2026-11-10.md`.

## Decisions (updated 2026-11-11)
1. Gallery #8 — CONFIRMED by Luke 2026-11-11: use the image-accurate
   title "Buildable Slopes by Lava Hot Springs — binary version".
   (Wix title was "Vegetation by Lava Hot Springs".)
2. Gallery #23 — CONFIRMED by Luke 2026-11-11: use the image-accurate
   title "Street Intersections per Square Mile by Neighborhood,
   Bellingham, WA". (Wix title was "Total Population by Square Mile
   by Neighborhood, Bellingham".)

## Still open
3. Reports #2 "Using Trees in Stormwater Management" — Wix links to
   "Trees as a Green Infrastructure Intervention.pdf", not to
   "Trees in Stormwater Management.pdf". Three similarly-named files
   exist in Drive. Confirm which file belongs to the tile.
3. Reports #2 "Using Trees in Stormwater Management" — Wix links to
   "Trees as a Green Infrastructure Intervention.pdf", not to
   "Trees in Stormwater Management.pdf". Three similarly-named files
   exist in Drive. Confirm which file belongs to the tile.
4. Optional: 12 extra items in the Drive Report References folder are
   not on the Wix Reports page (e.g. Economic Impact Study on Samish
   Way, GIS Hydrographic Analysis, Green Roofs in Urban Passive
   Cooling, Nephi Tech Assessment, Review of Encampment Dashboard
   Best Practices). Say which, if any, to add.

## Free hosting options for this folder (no rebuild needed)
- **GitHub Pages** (recommended for $0, no ads, no badge, custom
  domain supported): create a repo, upload this folder, enable Pages.
  ~15 MB total, well under the ~1 GB limit.
- **Netlify Drop**: drag this folder onto drop.netlify.com — instant
  free URL, no account build step.
- **Cloudflare Pages**: same drag-and-drop / git flow, free.
- Google Sites was the other practical option discussed 2026-11-10,
  but it would need the gallery rebuilt by hand in its editor; this
  standalone folder is already built.

## Verify before publishing
- Open `index.html` locally; check all 23 gallery images load and
  all 16 report links open.
- Nothing here is published or submitted. Publishing is Luke's call.
