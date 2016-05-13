# leaflet-storymap-layers
Scroll-driven story map, with narrative text and multiple GeoJSON layers, using Leaflet and jQuery

## Demo
http://jackdougherty.github.io/leaflet-storymap-layers/index.html

## Features
- Scroll the storymap to add/remove GeoJSON layers and tell a story about changing lines or boundaries over time.
- Scroll-driven navigation, using screen swipe, trackpad, or keyboard down-arrow. Initial map displays all point markers. Viewers can pan and zoom the map independently of the narration to explore further.
- Easy-to-learn template to create your own storymap. Upload text, point coordinates, zoom levels, and image links to a CSV generic spreadsheet, and drag into http://geojson.io to create a GeoJSON data file.
- Images can be stored in local subfolder or pulled from an external URL.
- Works in modern browsers: Chrome, Firefox, Safari, Internet Explorer 9+.

## Requires open-source libraries
- Leaflet.js
- jQuery
- Font Awesome

## Compare with
- http://github.com/jackdougherty/leaflet-storymap
- http://github.com/jackdougherty/otl-historical-town-borders (also adds/removes tile layers via scroll)

## Credits
- Thanks @ilyankou for coding the add/remove layers with the scrolling interface  
- Adapted from MUX Lab, Map Effects 100: https://github.com/muxlab/map-effects-100, see http://muxlab.github.io/map-effects-100/Leaflet/11_scroll-driven-map-navigation.html

## Create your own version
- Start with map.csv template and add chapters, descriptions, zoom levels, center coordinates, images, layers
- Convert the map.csv into map.geojson with http://geojson.io
- Upload additional GeoJSON layer files (such as boundaries to be displayed) into layer folder
- See more details (to come) in http://DataVizForAll.org

## To Do
- Ilya's note: If for some reason the last chapter doesn't get active (the case for big screen sizes), replace value of areaTop in script.js from -100 to -200 or more.
- remove my placeholder images and create a richer story
- remove unnecessary files from the template and move to otl-version
- add polygon styling, display feature properties via click or hover
- add instructions in DataVizForAll.org
- explain how to add markers if desired
