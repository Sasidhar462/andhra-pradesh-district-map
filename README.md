# Andhra Pradesh District Explorer

Interactive Leaflet map with 28 Andhra Pradesh district records and links to the corresponding Notion notes pages.

## Features
- District polygons rendered from an open GeoJSON boundary dataset.
- Click a district to highlight it and select its Notion notes page.
- A district chip index remains available if the boundary data endpoint is unavailable.
- Quick notes can be saved in the current browser (local storage); permanent notes belong in Notion.
- Responsive layout for desktop and mobile.

## GitHub Pages
The repository uses GitHub Actions to deploy the static site from the `main` branch.

If GitHub Pages has not yet been activated for this repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.

Expected site URL:
https://sasidhar462.github.io/andhra-pradesh-district-map/

Map tiles © OpenStreetMap contributors. District boundary dataset is provided by the open `satdixit/india-shapefiles` repository. Boundaries are for general reference, not legal or cadastral use.
