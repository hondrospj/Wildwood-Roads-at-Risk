# Wildwood Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Wildwood municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01411360, Stone Harbor
- PETSS / NOAA station: 8535581
- NAVD88 thresholds: 3.44 ft minor, 4.44 ft moderate, 5.44 ft major
- MLLW thresholds: 6.1 ft minor, 7.1 ft moderate, 8.1 ft major
- MLLW = NAVD88 + 2.66 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Wildwood boundary at 5-foot resolution.
