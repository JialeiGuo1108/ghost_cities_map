# Global Ghost City Map
## Project Overview
This visualization aims to identify and map ghost cities around the world, defined as urban areas that have been built but remain mostly vacant or underutilized. According to the data sources, it explores the global distribution of ghost cities and compares the disparity between new and old urban areas using various measures, such as the road network density, points of interest (POI) density, population density, and land area. By quantifying these differences, an index called Ghost City Index(GCI)  is utilised to measure the vitality differential between modern and old urban regions, emphasising places at risk of neglect or abandonment.

## Data Sources
The visualization integrates data from three primary sources:

1.Natural Earth Data: Base country boundaries and geographical reference(https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-admin-0-countries/);

2.BCL-Global-Ghost-Cities dataset (Mendeley Data): Core ghost city identification and metrics(https://data.mendeley.com/datasets/ypj9s32tn6/1).

## Visualisation Method
For the interactive portion of the project, Mapbox leverages styles and vector tiles for efficient rendering of global data, to show the distribution of global , the vitality index of new and old urban areas, and the ghost city index. Interactive popups reveal detailed index values when users hover over cities on the ghost city map. The statistics are also presented in the sidebars comparing urban area metrics of the new and old regions using continents in the application with the help of the Chart.js library. Custom map layers with data driven styling are provided enabling users to see different modes of visualization for patterns of urban development across the globe.

## Page layout and design
The design employs a dark-themed interface with a three-panel layout, where the left and right sidebars contain statistical information and comparative charts, while the central panel features an interactive global map. The color scheme uses high-contrast gold/amber highlights against a black background, with a carefully designed color progression to represent the Ghost City Index severity. 

The visualization contains multiple linked views to allow users to understand the phenomenon from different perspectives:

1.A global map displaying ghost cities as interactive circular markers;

2.Bar charts comparing urban vitality metrics across continents;

3.Country rankings showing the distribution of ghost cities globally;

4.Switchable map layers to toggle between ghost city distribution, GCI values, and the vitality of new versus old urban areas.

Interactive elements enhance exploration through region-specific zooming, detailed hover popups, and dynamic chart panels that respond to selected indicators. This layered approach reveals stark contrasts between old and new urban developments while illuminating global patterns of ghost city distribution.

## Web link
https://jialeiguo1108.github.io/ghost_cities_map/global_ghost_cities.html

(⚠️ Due to the volume of global data, initial load may take a moment — please allow a few seconds for the map to fully render.)
