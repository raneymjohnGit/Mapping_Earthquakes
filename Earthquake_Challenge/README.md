# Mapping_Earthquakes
For learning Java Script with APIs from Module 13

## Project Overview
Basil and Sadhana like how you created your earthquake map with two different maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.
## Resources
- javascript, HTML, Bootstrap, Visual Code, Browser Edge
- JSON data  
## Challenge Overview
Prerequisite:
1.  Download the tectonic_plate_starter_logic.js and major_eq_starter_logic.js


## Deliverable 1:  Add Tectonic Plate Data

Follow the instructions below and the numbered comments in the starter code to complete Deliverable 1.

1. Download the tectonic_plate_starter_logic.js file, add it to your js folder, and rename it challenge_logic.js.
2. Add a second layer group variable for the tectonic plate data.
3. Ad a reference to the tectonic plate data to the overlay object.
4. Using d3.json() callback method, make a call to the tectonic plate data using the GeoJSON/PB2002_boundaries.json data from this GitHub repository (Links to an 
    external site.) for the tectonic plate data. You’ll need to log into GitHub to access the GeoJSON data.
5. Pass the tectonic plate data to the geoJSON() layer.
6. Style the lines with a color and weight that will make it stand out on all maps.
7. Add the tectonic layer group variable you created in Step 1 to the map, i.e., .addTo(tectonicPlates) and close the geoJSON() layer.
8. Add the tectonic layer group variable to the map, i.e, tectonicPlates.addTo(map).
9. Finally, close the d3.json() callback.
10. Start your Python server and launch the index.html file and confirm that your map with the earthquake and tectonic plate data is there.

## Deliverable 2:  Add Major Earthquake Data
1. Add a third layer group variable for the major earthquake data.
2. Add a reference to the major earthquake data to the overlay object.
3. Use the d3.json() callback method to make a call to the major earthquake data from the GeoJSON Summary Feed for M4.5+ Earthquakes (Links to an external site.) 
    for the Past 7 Days.
4. Use the same parameters in the styleInfo() function that will make a call to the getColor() and getRadius() functions.
5. Change the getColor() function to use only three colors for the following magnitudes; magnitude less than 5, a magnitude greater than 5, and a magnitude greater 
    than 6.
6. Use the same parameters from the preceding step in the getRadius() function.
7. Pass the major earthquake data into the GeoJSON layer and do the following with the geoJSON() layer:
8. Turn each feature into a circleMarker on the map
9. Style each circle with styleInfo() function
10. Create a popup for the circle to display the magnitude and location of the earthquake
11. Add the major earthquake layer group variable you created in Step 1 to the map, i.e., .addTo(majorEQ) and then close the geoJSON() layer.
12. Add the major earthquake layer group variable to the map, i.e, majorEQ.addTo(map), and then close the d3.json() callback.
13. Start your Python server and launch the index.html file and confirm that your map with the two earthquake data sets and tectonic plate data are there


## Deliverable 3:  Add an Additional Map 

1. Using the options from the Mapbox styles (Links to an external site.), add a third map style as a tile layer object to the challenge_logic.js file.
2. Add the map variable to the base layer object.
3. Start your Python server and launch the index.html file and confirm that your map is similar to the following image, where there are three map styles, and 
   displays the two earthquake data sets and the tectonic plate data.

## Final Earthquake Data 
  - Final image after completing Delverabel 1 , 2 and 3
    ![image_name](https://github.com/raneymjohnGit/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/EarthquakeDataOnMap.png)