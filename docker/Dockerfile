FROM jupyter/datascience-notebook

MAINTAINER Chonghua Yin<royalosyin@gmail.com>

# Install meteo-specific libs
RUN conda install --quiet --yes -c conda-forge dask cfgrib metpy

WORKDIR /notebooks

VOLUME /notebooks 
