## Talk Flow 

Intro to ESRI 
  * Jack D 1969
  * Making Maps thru spatial analysis, blah blah
  * GIS: Deriv information from spatial data
  * Esri makes software and services that enable this  


Talk about our use of github?
  - GeoIQ Aquired 
  - Anything that can be open should be open 
  - esri.github.com 


Intro ArcGIS
  * Desktop analysis and cartography 
  * Web maps -> ArcGIS Online
    * think dropbox for maps 


Intro to FeatureServices 
  * Explain what the API is and how it works 
  * What makes it special, spatial
  * What are the challenges? - maybe not 


ArcGIS Open Data 
  - enable any organization to host curated sets of data
  - provide various formats and APIs 
  - for free 
  - maintainability


Koop 
  - ETL Engine for Open Data 
  - ETL for APIs 
  - Also an R&D project
    - new to share data and think about how our user interact with data on the web.

  Overview
  - Introduce Koop 
  - Walk through a few examples of how can be used
  - Show some of the R & D efforts 
  - Talk applying Koop to OpenStreetMap

So what is Koop? 

  - A modular node.js application that interacts with various APIs and Caches data into a spatial database 
  - From there it exposes data as Esri Feature Services and GeoJSON 
    - also exports data as shp, csv, kml, etc...
 
Examples: 

  - The github work flow 
    - show something compelling in Github 
  - The socrata workflow 
    - show data from socrata mapped within ArcGIS Online 
  - Raw data demo 
    - Show the wind map 
    - Show the climate grids 
    - Show the grid interpolation 
    - Talk about where its going 
      eg new formats for data transfer, ArrayBuffers to pass grids

OpenStreetMap and Koop 
  - OSM as a resource of data
    - points, lines, polygons 
    - Rich amount of content not directly, or easily, consumable
      - esp. by GIS users who are not specifically developers 
  - A Koop adapter to OSM 
    - aids in discovery and accessiblity with the goal of extracting content out for use in GIS applications 
  - Applying restful access 
    - Searching for data 
    - accessing geojson
      - pipe it geojsonio 
      - Bring it into AGOL 
        - run an analysis 

Whats next? 
  - Thinking about more OSM data in the ArcGIS platform by way of Open Data 
    - organizations might have the option to include curated sets of OSM exports for thier locations 
  - How might we apply OSM tools like ID to edit GIS dataset thru Esri's GeoServices REST.

TODO 

1. Rough the slides together by tomorrow night w/images 
2. Make koop osm talk feature service 

