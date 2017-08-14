# Functions for raster calculations in ArcGIS and Python

This notebook shows how to use luminosity satellite imagery (freely available) to calculate access to electricity on a county level in Romania.
This notebook shows several key ArcGIS Python functions such as:

- reprojecting shape and raster files to the relevant projection system
- clipping rasters to the shape of a polygon (extract by mask)
- Calculating Zonal Statistics and importing the values back to the polygon attribute table
- Analysing the resulting data using matplotlib.pyplot

The code can be obviously used for other types of raster files such as DEM.
