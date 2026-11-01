# Granite & Giants — Thanksgiving 2026

A responsive, buildless trip website for a proposed November 26–30 Yosemite and Muir Woods itinerary. All times are Pacific. Nothing is booked through this site.

## Run locally

Serve this directory with a static server, for example `python3 -m http.server 4173`.

## Edit

- `index.html`: stays, budget, maps, preparation and sources.
- `app.js`: five timed days, Friday's YARTS alternative, map selection, print and sharing behavior.
- `styles.css`: desktop, mobile and print layouts.

## Deployment

GitHub Pages serves the root of `main`. The `.nojekyll` file preserves the plain static layout. No build step or server secrets are required.

## Data and images

Research date: November 1, 2026. The Yosemite hotel quote is an earlier observed quote, not a held reservation; the Marin room budget is an allowance, not a rate. Exact weather, availability and conditions must be rechecked before travel.

Landscape images are externally hosted National Park Service photography. Muir Woods trail photography is credited to NPS / Jason Bosinoff; Cathedral Grove to Alison Taggart-Barone and Battery Spencer to Kirke Wrench via NPS. Day-specific photo galleries link to each source and label seasonal differences, including the April/August Mirror Lake comparison. Hotel images are externally hosted by Yosemite Resorts, which retains its image rights. The displayed river-view balcony is illustrative and is not the quoted Mountain View room. See the site's source section for links and credits.

The site embeds Google Maps and loads Google Fonts. It includes no analytics or booking/payment form. Checklist state is stored only in the visitor's browser. `noindex` requests exclusion from search indexing; the published site remains publicly accessible to anyone with its URL.
