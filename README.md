# Takoma-Park-Tax-Assessment



Takoma Park Regression rmd file:
This file contains the code that conducts the statistical analysis for the project. The only library being used in this file is readr which enables the reading of csv files. The one linear regression model and two logistic regression models can be seen in this file, as well as the conclusions drawn from each model. 

Spatial Interactive Python Notebooks:
Libraries used:
<ul>
  <li>Pandas/Geopandas = dataframe libraries, used to handle tabular data</li>
  <li>Shapely = handles vector geospatial data</li>
  <li>Numpy = Matrix operations in efficient framework wrapped in C code (good for larger datasets)</li>
  <li>Matplotlib = Basic non-interactive graphs</li>
  <li>os & sys = handles file paths</li>
  <li>pysal.lib.weights = used to create spatial weights matrix in order to run spatial autocorrelation tests</li>
  <li>pysal.explore.esda = exploratory spatial data science package that contains the Moran's I statistical tests</li>
  <li>pysal.viz.splot.esda = autocorrelation plots for Moran's I tests</li>
  <li>h3 = library created by Uber that geohashes the planet into equal area hex bins of varying resolution</li>
  <li>tolbler.util h3fy = an extension of the Tobler spatial package that enables ease of use for feeding in various shapefiles for easier hex binning</li>
  <li>geocage = Python geocoder that utilizes and compares results from a number of geocoding sources. requires API key</li>
</ul>
