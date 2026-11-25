# Land Change Atlas

An interactive report on how the land changed at three places, mapped year by year from
open satellite imagery (Sentinel-2 and Landsat):

- Dallas-Fort Worth, Texas
- North Istanbul, Türkiye
- Kakhovka Reservoir bed, Ukraine

**Open the report: <https://efkopru.github.io/land-change-atlas/>**

This repository holds only the built page: `index.html`, its data (`data.js`) and the map
images under `layers/`. All of it is generated, so a change made here by hand is overwritten
by the next build. The page loads nothing from other servers.

## Credits

- Contains modified Copernicus Sentinel data (Sentinel-2, read from Earth Search).
- Landsat Collection 2 and LCMAP courtesy of the U.S. Geological Survey, read from
  Planetary Computer.
- Impact Observatory annual land cover (Impact Observatory, Microsoft and Esri), regrouped
  into the report's classes and resampled to its grid, used under
  [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- Global Surface Water: EC JRC/Google.
- ESA CCI land cover, used as an outside check: ESA Climate Change Initiative and
  Copernicus Climate Change Service (doi:10.24381/cds.006f2c9a).
- Boundaries: U.S. Census Bureau.
- The map is drawn with [Leaflet](https://leafletjs.com) 1.9.4, used under the BSD 2-Clause
  licence. Its text is in [`leaflet-LICENSE.txt`](leaflet-LICENSE.txt).
