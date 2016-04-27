# leaflet-storymap-layers
Scroll-driven story map, with narrative text and multiple GeoJSON layers, using Leaflet and jQuery

## Demo
http://jackdougherty.github.io/leaflet-storymap-layers/index.html

## Features
- Scroll the storymap to add/remove GeoJSON layers and tell a story about changing lines or boundaries over time.
- Scroll-driven navigation, using screen swipe, trackpad, or keyboard down-arrow. Initial map displays all point markers. Viewers can pan and zoom the map independently of the narration to explore further.
- Easy-to-learn template to create your own storymap. Upload text, point coordinates, zoom levels, and image links to a CSV generic spreadsheet, and drag into http://geojson.io to create a GeoJSON data file.
- Images can be stored in local subfolder or pulled from an external URL.
- Works in modern browsers (Chrome, Firefox, IE, Safari, including 1st generation iPad). Not supported in IE 8 or lower.
- Uses only free and open-source Leaflet.js and jQuery libraries.

## Create your own version
- Start with map.csv template and add chapters, descriptions, zoom levels, center coordinates, images, layers
- Upload GeoJSON layer files to be displayed into the layer folder
- Convert the map.csv into map.geojson with http://geojson.io
- See more details (to come) in http://DataVizForAll.org

## Compare with
- http://github.com/jackdougherty/leaflet-storymap

## Credits
- Thanks @ilyankou for coding the add/remove layers with the scrolling interface  
- Adapted from MUX Lab, Map Effects 100: https://github.com/muxlab/map-effects-100, see http://muxlab.github.io/map-effects-100/Leaflet/11_scroll-driven-map-navigation.html

## To Do
- confirm all mobile devices (including iPad 1st Gen?)
- Ilya's note: If for some reason the last chapter doesn't get active (the case for big screen sizes), replace value of areaTop in script.js from -100 to -200 or more.
- remove my placeholder images and create a richer story
- remove unnecessary files from the template and move to otl-version
- add polygon styling, display feature properties via click or hover
- add instructions in DataVizForAll.org
- explain how to add markers if desired
