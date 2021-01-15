# Special Topics in Remote Sensing Personal Homework
## Introduction
This repo is for **personal homework**.

This repo includes input and output files of project and Jupyter notebook file which I worked on.

In this project,Normalized difference water index which is used to monitor changes related to water content in water bodies was calculated with Green and NIR bands of a Landsat 5 image.

Formula for NDWI:


<a href="https://www.codecogs.com/eqnedit.php?latex=\dpi{300}&space;\tiny&space;NDWI&space;=&space;\frac{Green-NIR}{Green&plus;NIR}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dpi{300}&space;\tiny&space;NDWI&space;=&space;\frac{Green-NIR}{Green&plus;NIR}" title="\tiny NDWI = \frac{Green-NIR}{Green+NIR}" /></a>

## Used libraries:
- **numpy** for converting images to arrays and calculate NDWI,
- **skimage** to create histogram of output,
- **rasterio** to open rasters and write rasters,
- **matplotlib** to plot outputs.

## Inputs and Output
![Green Band](Screenshots/Green.png?raw=true "Title")


![ITU Logo](https://www.iotlinefair.com/wp-content/uploads/2015/04/itu-logo.jpg)
