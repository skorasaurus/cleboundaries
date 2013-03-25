cleboundaries
=============

Boundaries of Cleveland wards, current, and proposed, etc. 

some of the TODO: 
- find existing city of cleveland ward boundaries (SHP would work)
- finish drawing the boundaries for 2013
- load each, separately into tilemill
- make the tilemill projects for the streets baselayer. 


Inspired by: 

http://project.wnyc.org/nyc-districting-revised/index.html?lat=40.7370&lon=-73.9220&zoom=12


1. obtain census tracts with population inside them from http://www.census.gov/geo/maps-data/data/tiger-data.html

there's 2 commands that I Found:
ogr2ogr -f "ESRI Shapefile" borders_north.shp borders.shp -clipsrc -180 0 180 90


