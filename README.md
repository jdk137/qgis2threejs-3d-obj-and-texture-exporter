# qgis2threejs 3d obj and texture exporter

Export obj and texture image from output file of qgis2threejs.

Usage:

1. replace content of index.js 

	If output file of qgis2three is your_output_name.html, then copy content of your_output_name.js into index.js.

2. open index.html in chrome browser
    .obj file and .html file will be downloaded auto. 

3. Open the html file, right click the image and save as png.

Project detail:
   
1. This project is based on original qgis2threejs output file. Add threejs's OBJExporter.js to export obj. 

2. The reason not export png file directly is it's a more general way to get png in different OS.

3. If there are multi image layers, then multi texture layers will be downloaded.



