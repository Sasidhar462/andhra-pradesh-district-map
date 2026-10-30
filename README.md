# Andhra Pradesh District Explorer

An interactive Leaflet map for the current 28-district configuration of Andhra Pradesh, with direct links to each district's Notion notes page.

## Districts and updates
- Includes the two districts created with effect from 31 December 2025: **Markapuram** and **Polavaram**.
- Retains **Sri Potti Sriramulu Nellore** as a district; it was not abolished. Its boundary changed in the 2025 reorganisation.
- Reads current district boundary relations from OpenStreetMap (Overpass API), rather than using the older pre-2025 GeoJSON boundary file.
- Verifies that all 28 districts match before displaying the boundary layer. The district list still works if the boundary API is unavailable.
- Clicking a polygon or district chip selects the district and exposes its Notion notes link.

## Deploy
Published as a static site with GitHub Pages from the `main` branch root.

https://sasidhar462.github.io/andhra-pradesh-district-map/

## Sources and attribution
- Government of Andhra Pradesh final Gazette notifications dated 30 December 2025, effective 31 December 2025.
- OpenStreetMap administrative boundary relations (admin_level=5), queried dynamically through Overpass.
- © OpenStreetMap contributors. Boundary data is under the Open Database License (ODbL). Map geometry is for general reference, not legal or cadastral use.
