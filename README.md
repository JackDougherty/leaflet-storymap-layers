# leaflet-storymap-layers
Scroll-driven story map, with point markers and narrative text and multiple GeoJSON layers, using Leaflet and jQuery

## Demo
http://jackdougherty.github.io/leaflet-storymap-layers/index.html

## Goal

Scrolling the storymap adds/removes GeoJSON layers, to tell a story about changing boundaries over time

Coding suggestion: use add/remove layer to make background geojson appear/disappear with scroll movement
- http://leafletjs.com/reference-1.0.0.html#layer
- http://gis.stackexchange.com/questions/118510/load-or-display-differents-geojson-data-on-zoom-level-for-leaflet-maps

The map.geojson file now includes a layer property, which refers to the layer folder: layer1.geojson, layer2.geojson, layer3.geojson
