# Mapping_Earthquakes
## Purpose
The purpose of this project was to utilize JavaScript and the D3 library with a Mapbox API to create a Leaflet map populated with GeoJSON earthquake and tectonic plate data. The maps were customized using JavaScript ES6 to display the earthquake magnitude using colors and popup markers on a local server. Another major aspect of this project was learning how to create and merge GitHub branches to practice project management practices.

## Results
### Deliverable 1: Add Tectonic Plate Data
First, I created an tectonic plate overlay, similar to the earthquake overlay that was first populated on the map. I added the tectonic plate overlay to the legend, so the user could choose whether or not to display the tectonic plate lines layer on the map. The tectonic plate layer was created by using the D3 library to access and pass the tectonic plate JSON file to the GeoJSON layer. The tectonic layer group variable was added to the map and displayed with a thick red line to show up on every map type. 
<img width="1439" alt="Screen Shot 2021-09-17 at 1 13 46 PM" src="https://user-images.githubusercontent.com/85946042/133840685-b126e93f-545f-45e9-b789-d80d0b2ddbbd.png">
<img width="722" alt="Screen Shot 2021-09-17 at 2 04 23 PM" src="https://user-images.githubusercontent.com/85946042/133840736-27c4d1da-24d4-44de-909f-76ad00e287c4.png">


### Deliverable 2: Add Major Earthquake Data
To add the major earthquake data to the map, I created an overlay like the earthquake and tectonic plates overlays. I added this to the legend, so the user could choose whether or not to populate the map with the major earthquakes layer. The major earthquakes layer was created by using the D3 library to access and pass the GeoJSON data on the major earthquakes with magnitudes above 4.5 from the last 7 days to the GeoJSON layer. The major earthquake layer was styled much like the original earthquake layer, with circle maker radius related to earthquake magnitude, but the colors were updated to reflect magnitudes only above 4.5. Earthquakes above 6 magnitude were now displayed with a darker red circle. The same marker popup is used as the first earthquakes overlay layer to display the earthquake magnitude and location when clicked.
<img width="838" alt="Screen Shot 2021-09-17 at 1 38 29 PM" src="https://user-images.githubusercontent.com/85946042/133840582-94eac35a-c649-451c-862a-a357f9c4a921.png">
<img width="1420" alt="Screen Shot 2021-09-17 at 2 03 33 PM" src="https://user-images.githubusercontent.com/85946042/133840665-5ed9b909-c0c9-4244-ad41-1156723dfb42.png">



### Deliverable 3: Add an Additional Map
Finally, I added a third map style, "dark," to the earthquake map. The dark layer was created by adding a third tile layer and using the Mapbox styles for a dark tile layer. I added the dark tile layer to tbe base layer object so that it would also appear in the legend for the user to choose which map style to display.
<img width="836" alt="Screen Shot 2021-09-17 at 1 36 18 PM" src="https://user-images.githubusercontent.com/85946042/133840541-5e31e2c9-d2c8-4147-a7d2-f233da555030.png">

<img width="839" alt="Screen Shot 2021-09-17 at 1 38 39 PM" src="https://user-images.githubusercontent.com/85946042/133840527-a7981769-3da1-48dc-9456-424f427a570b.png">


## Summary
During this challenge I was able to add multiple overlays to the map to dynamically display tectonic plate lines and major earthquakes that could both be toggled on or off by the user in the legend. I was able to customize the major earthquakes with color, size, and popup markers to give the user more information about each earthquake. After this challenge, I understand more about using the d3 library and JavaScript ES6 to map data usign Mapbox. 
