# airportwebmap.github.io

# Interactive Map Design

Bryan Begay
Oregon State University
GEOG 572
05/01/2019

##Background
This project was created during a lab for a geovisualization and cartography course at Oregon State University. The main objectives included understanding the key components and elements to create an interactive web map with symbology. In addition to creating a web map, other tasked included adding and customizing thematic laters, familiarization with base maps, legends, scales, and supplametal information.

The map created shows the number of airports in the United States, with information about whether control towers are present or not present at airport locations. A choropleth map was created using United States state level information that indicates by change in color how much airports are in each state.
## Some Functions used
* L.marker
  * Used to for marker objects.
* PointToLayer
  * Set icons in different colors, this function was used to helo process each feature and return a L.marker object.
* onEachFeature
  * This function was used to call on created features layers.
* onMapClick
  * A function that calls on parameters when the user clicks on the map.

## Libraries
leaflet.ajax
Font Awesome
jquery
Chroma-js

## Data Sources
Both data sources of airports and US states were provided by Geog572 professor Bo Zhao. The airports.geojson file was noted to be data convereted from a shapefiled that was unzipped from data.gov. The us-states.geo.json file was acquired from Mike Bostock of D3. Base map was found at CartoDB.

## Credit and Acknowledgments
Bo Zhao for data and lab information
data.gov for airports.geoJson
Mike Bostock of D3 for us-states.geoJson
CartoDB for CartoDB World Eco basemap
