# Andhra Pradesh District Notes Map

A static web app for exploring all 28 Andhra Pradesh districts and keeping a separate editable note for each district.

## Interaction

- Click a district marker on the map or a district in the index to open its notes drawer.
- The drawer includes a text editor, topic tags, word/character counts, previous/next district navigation, and a link to that district's Notion page.
- Notes auto-save to the browser's local storage under `ap_district_notes_v1`.
- Use **Copy note** or **Copy all notes for Notion** to copy Markdown, then paste it into Notion. The static site does not write directly to Notion.
- Search and filter districts by region or whether notes exist.
- Switch between street, satellite, and light map tiles.

District markers and the index remain interactive even when the optional OpenStreetMap boundary overlay cannot be loaded. Marker positions are representative district/headquarters locations, not legal boundary data.

## Current district set

Includes all 28 districts, including **Markapuram** and **Polavaram** (created effective 31 December 2025), and retains **Sri Potti Sriramulu Nellore**.

## Deploy

Published with GitHub Pages from the `main` branch root:

https://sasidhar462.github.io/andhra-pradesh-district-map/

## Attribution

- OpenStreetMap contributors (boundary and map data where available).
- CARTO and Esri basemap tiles.
- Boundary information is for general reference only, not legal or cadastral use.
