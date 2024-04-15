Materials for the course: **Web Mapping** 

## Why Web Mapping?
During the course, we will learn about techniques for publishing spatial information in the form of dynamic Internet maps. There are many reasons why this form of publication is actually dominant - convenience, the ability to make it available to a wide audience, dynamic content, the possibility of integration with Internet platforms and services (e.g. user geolocation) and, finally, the availability of a wide range of cartographic tools. The popularity of Internet cartography has resulted in the development of numerous technical solutions - the aim of this course is to present one of them. The tangible effect will be the creation of an internet map and its publication on the Internet.

## Topics of the classes
The list below presents a condensed version of what each block of classes includes, along with necessary materials and links to additional content.

1. **Introduction to the [Mapbox Platform](https://www.mapbox.com/) and creating a map style**
    - account registration (email from the university domain required)
    - spatial data structure in Mapbox: data sets, tiles, styles.
    - user interface, [tutorials](https://docs.mapbox.com/help/tutorials/), [examples](https://docs.mapbox.com/mapbox-gl-js/example/), [documentation ](https://docs.mapbox.com/),
    - [Mapbox Studio](https://studio.mapbox.com/) - available resources, map styling using components
    - **Task 1** - *create your own visually consistent style by changing the properties of components. Share as a preview*
2. **Editing the map style for layers and adding your own data**
    - advanced style editing using layers
    - add your own data and create a set of tiles
    - data visualization methods in Mapbox
    - data import: formats and requirements
    - creating and editing data using [Mapbox Editor](https://studio.mapbox.com/datasets/)
    - publication of a map preview
    - **Task 2** - *Create a map showing the distribution of the feminization rate on the example of Poznań. Use 3D visualization. Use [Poznań demographic dataset](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/demography_poznan.geojson)*
3. **Advanced Layer Styling**
    - styling of line and point layers
    - data-dependent styling
    - heat maps
    - layer groups
    - icons and fonts
    - scale-dependent styles
4. **Publishing the map using the website - Mapbox GL JS**
    - creating your own website with a web map based on [Mapbox simple map example](https://docs.mapbox.com/mapbox-gl-js/example/simple-map/)
    - website structure (CSS, HTML)
    - basics of JavaScript
    - browser development tools
    - introduction to the Mapbox GL JS library
    - **Task 3** - *Publish your own style as a website - html file*
5. **Adding interactive features to the map**
    - adding interactive functions to the map - [example with popups](https://docs.mapbox.com/mapbox-gl-js/example/popup-on-click/)
    - switching map layers using Javascript functions - [example](https://docs.mapbox.com/mapbox-gl-js/example/toggle-layers/)
6. **Final assignment**
    - **Task 4 - final project** - *Task in groups of 1-2 people. Create and publish your own website with a map on your chosen topic. Use any data except those used in class. The cartographic part (readability, selection of colors and symbols, visual hierarchy, etc.) and the functional part (degree of interactivity, added functions) will be assessed. *

## Sample data

1. [Voivodships (file poland_voivodships.geojson)](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/poland_voivodships.geojson)
_Provincial boundaries and sample attribute data._
2. [Demographic data for Poznań (demography_poznan.geojson file)](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/demography_poznan.geojson)
_2011 Census data: Grid with population, age and gender._
3. [Natural monuments in Poznań (natural_monuments.csv file](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/natural_monuments.csv)
_Natural monuments near Poznań from GDOŚ - CSV format_
4. [Natural monument marking icon (file natural_monument.svg](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/natural_monument.svg)
_Icon in SVG format_
5. [Data from bicycle counters for Poznań (file dzienniki_rowerowe_Poznan_21032024.geojson](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/liczniki_rowerowe_Poznan_21032024.geojson)
_Icon in SVG format_
6. [Value of car noise emission in Poznań - LN index (halas_zdrowie_LN.geojson file)](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/halas_zdrowie_LN.geojson)
_Icon in SVG format_

## Publication of the map on the Internet - hosting services
Certainly, at some point the created map must be made publicly available. For this you need space on the server (hosting). There are many platforms that allow free hosting, but you have to be careful (e.g. unwanted ads) and not all of them are user-friendly. Personally, I recommend two ways of publishing to start with:

1. [GitHub Pages](https://pages.github.com/) - a very simple and flexible way to publish a page to a GitHub repository (like this)
2. [Gitch](https://glitch.com/) - a free account that allows not only publishing a static website but also testing the construction of web applications


## Alternative software
Mapbox was chosen because it is a relatively closed solution and does not require knowledge of any programming language to create a readable map with basic functionality. But if you want something more, all you need are the basics of Javascript, HTML and CSS and the world of web maps is open to you. The basics of these three things are also needed when using Mapbox in a more advanced way. Alternative ways to create web maps for Mapbox (in no particular order):

1. [Leaflet](https://leafletjs.com/) - one of the most popular map libraries. Easy to implement, many extensions and integrations with GIS software and more, e.g.:
    - QGIS + [qgis2web plugin](https://plugins.qgis.org/plugins/qgis2web/) - a user-friendly plugin that allows you to export a QGIS project both as a map made in Leaflet and in OpenLayers (see below)
    - R + [Leaflet library](https://rstudio.github.io/leaflet/) a very interesting option for people working in the R programming environment
2. [ArcGIS Online](https://www.arcgis.com/index.html) - a proprietary platform that allows you to publish maps in many different ways (e.g. Story Maps), also for free to a limited extent. Advanced capabilities combined with ArcGIS/
3. [OpenLayers](https://openlayers.org/) - a very extensive and very well described mapping platform, an alternative to Leaflet (although it requires slightly more programming skills)
4. [MapLibre](https://maplibre.org/) - Open Source version of the Mapbox GL JS programming libraries. If you do not need Mapbox services such as Studio and the goal is to create a clear and functional map for the website, if you have knowledge of Javascript, it is worth considering a free alternative.


## To read

1. [W3Schools HTML Course](https://www.w3schools.com/html/)
2. [W3Schools CSS Course](https://www.w3schools.com/css/)
3. [W3Schools Javascript Course](https://www.w3schools.com/js/)
