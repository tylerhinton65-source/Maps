# Land Finder — Utah & Wyoming

Map overlays for scouting land to buy in Utah and Wyoming.

Two versions share the same data:
- `index.html` — Land Finder (personal land scouting)
- `politics.html` — Precinct Map (election-only version)

Open either file in a browser to run it.

## Data credits
- 2024 presidential results by precinct: [The New York Times](https://github.com/nytimes/presidential-precinct-map-2024), used under its non-commercial license (see `data/NYT-LICENSE.txt`). Shapes simplified for faster loading.
- 2026 general results by precinct: [Wyoming Secretary of State](https://sos.wyo.gov/Elections/Docs/2026/2026GeneralResults.aspx) (official) and [Utah County Elections](https://vote.utahcounty.gov/results) (official canvass). Utah precinct boundaries: [UGRC Vista Ballot Areas](https://gis.utah.gov/data/political/voter-precincts); Wyoming reuses the 2024 NYT shapes.
- 2026 Utah results outside Utah County, and Utah statewide totals: [Utah Lt. Governor's results site](https://electionresults.utah.gov/results/public/Utah/elections/General11032026) (county-canvassed; statewide canvass pending), shown by county until precinct reports are added. Utah County state senate by precinct: Utah County's official results service. County outlines: U.S. Census TIGERweb, loaded at runtime. Stored in `data/results-2026-statewide.json`.
- Land ownership: Bureau of Land Management Surface Management Agency.
- Base maps: Esri, USGS, OpenStreetMap contributors.
