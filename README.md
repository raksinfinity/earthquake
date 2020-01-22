# earthquake
This project consits of a D3js visualiztion of the most significant earthquakes in the last 1 month according to USGS.
The exists in the form of GeoJson format.
The project gives a dynamic visualization of the earthquake that occured and the ouput varies dynamically based on the data.
The Circle indicates an earthquake and important parameters like time, magnitude and location is considered.
The files:
new.html -> includes a div tag and script tags for java script file, d3js and css file.
app.cs -> contains styling for div and tooltip
quake.js -> describes the html body with circles indicating earthquakes. Consists of creation of mouseon and mouseout events with a tooltip. Also the system needs to be connected to the internet for the data to be fetched in real time.
