# A Statewide Siting Tool for Coastal Enhanced Weathering on the California Coast

Ella Coulson, Connor Mack — Scripps Institution of Oceanography, UC San Diego

Live site: **https://ellabcoulson.github.io/ca-cew/**

Coastal enhanced weathering spreads crushed silicate minerals on sandy beaches. Wave energy
grinds them down, and the reaction draws CO₂ out of the atmosphere and stores it in seawater
as dissolved bicarbonate. This work asks where along the California coast that could happen,
across 3,148 one-kilometre shoreline segments.

## What is here

| | |
|---|---|
| `index.html` | Landing page |
| `interactive_maps/ca_cew_suitability_map.html` | **Suitability Map** — the June 2026 capstone version, which combines every layer into a composite score |
| `interactive_maps/ca_cew_merged_map.html` | **Siting Tool** — the current screen: same segments, no composite score, each threshold stated on its own |

The two maps are the same screen before and after. The capstone version ranks; the current
one deliberately does not — the layers are reported side by side so a reader can see what each
threshold does and disagree with it.

## Notes

Both maps are single self-contained HTML files with their data embedded, so they open from
disk as readily as from the web. They are large by web standards (10.5 MB and 27 MB) and take
a moment to load on a slow connection.

Basemap tiles are served by Esri and require a network connection; everything else — geometry,
segment cards, layer logic — is in the file.

The pipeline that produces the segment data and builds these maps is not published here.

*Manuscript in preparation. Counts are the June 2026 statewide run.*
