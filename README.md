# USGS Earthquake Data Visualization using the Bokeh Library

This Jupyter notebook pulls data from the USGS Earthquake Hazards portal and visualizes the dataset using the Bokeh library.

* USGS Earthquake data is retrieved as GeoJSON and then parsed into a dataframe for Bokeh

**USGS Data Resources**
* [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/)
* [USGS Earthquake Hazards Program: GeoJSON Summary Format](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
* [USGS Volcano Hazards Program](https://volcanoes.usgs.gov/observatories/hvo/hvo_earthquakes.html)

**Bokeh Visualization Library**
* [Bokeh](https://bokeh.pydata.org/en/latest/)
* [Bokeh Tutorial: Geographic Plots](https://hub.mybinder.org/user/bokeh-bokeh-notebooks-8dydb5oj/notebooks/tutorial/09%20-%20Geographic%20Plots.ipynb)

Note: When plotting geospatial data in Bokeh, WGS84 coordinates must be first converted to Web Mercator format in order to be visualized properly.

**Geospatial Resources**
* [World Geodetic System](https://en.wikipedia.org/wiki/World_Geodetic_System)
* [WGS84](https://wiki.gis.com/wiki/index.php/WGS84)
* [Web Mercator](https://en.wikipedia.org/wiki/Web_Mercator)
