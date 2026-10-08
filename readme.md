# Ciacova to Timișoara

## Introduction
This interactive web map traces the bus route between the town of Ciacova and the city of Timișoara, Romania. The route runs north across the region of Banat, passing through Jebel and Șag before arriving at the Autogara Super Imposer bus station in Timișoara. I took this route many times from my site to the city and locations beyond.

## Major Functions
- Displays the full bus route as a styled, dashed line
- Marks four stops: Ciacova, Jebel, Șag, and Timișoara
- Shows the name of each stop in a tooltip on mouseover
- Supports panning and zooming, and opens fitted to the route's extent

## Libraries
- [Leaflet](https://leafletjs.com/) for the interactive map
- [Normalize.css](https://necolas.github.io/normalize.css/)
- Google Fonts (Lora, Noto Sans) for styling

## Data Sources
- Route generated with Google Maps directions, converted to GPX with Maps to GPX, and edited into GeoJSON with [geojson.io](https://geojson.io)
- Basemap: [Esri World Street Map] via [Leaflet Providers](https://github.com/leaflet-extras/leaflet-providers)
