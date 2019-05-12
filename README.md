# DockerMet
Using Docker Compose to rapidly deploy a Jupyter Notebook environment for processing meteorological and climatic data. The Dockerfile was created based on the data-science stack image from Jupyter project. Besides default tools and packages, only add several met-clim specific packages such as xarray and dask for netCDF, sfgrib for Grib1/2,  and MetPy for met.

A demo data from real-time GFS forecast was also provide in the folder of data. A tutoiral notebook was put under the folder of notebooks. :) The demo notebook explained how to create this DockerMet project, however without providing the correponding images.
