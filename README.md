# First QGIS project 

This training is designed for complete beginners with GIS data. 

## When to use QGIS

Scenario | Tool | Reason | Example
---------|-------|-------|-----------
Have data for a 50-state cartogram or geographic map | Datawrapper | No advanced functionality needed; this can be done quicker and with the pre-loaded shpfiles already in Datawrapper | Cartogram showing marijuana legalization by state 
Plotting points on a map | Datawrapper or QGIS | If Datawrapper has the level of detail you want on the map (roads, water, etc), then this is faster and easier to do in DW. If, however, you need to add additional layers (topography, custom borders, etc.), then you'll need to bring those layers into QGIS and plot the points there. | Superfund cleanup sites (Datawrapper); Drilling proximity to wildlife reserve custom shapefile (QGIS)
Mapping multiple shapefiles | QGIS | Datawrapper only allows one custom geojson per map. | Mapping California congressional districts overlaid with Indian reservations
Analyzing geographic data (i.e. calculating number of points in a shape) | QGIS or Python | QGIS can easily do geographic analysis with just a few clicks. If, however, you need to repeat the analysis several times, automating it in Python may be better. This could be the case, for example, if you are trying to do a separate analysis for multiple cities or states. | Number of grocery stores per Census tract in one city (QGIS); Census demographic analysis of downtown districts in 100 cities (Python)


**In general**, Datawrapper is best for mapping when the visualization is simple and doesn't need much customization. QGIS is best for mapping when you need to bring in custom layers, and for one-off geospatial data analysis. Python is best for repetitive geospatial data analysis.

## What we'll cover

* Basics of QGIS
	* Toolbars/menus
	* Data types (polygons, points, delimited files)
	* Attribute table
* A simple map
	* Combining polygons and points 
	* Symbology
	* How to export to Illustrator
* A simple analysis
	* Counting points 
	* How to export to Excel
* Combining CSVs (delimited files) and shapefiles
	* Make a choropleth Census tracts
* Merging shapefiles
	* Cities with Census blocks 
* Projections - how to change and troubleshoot 





