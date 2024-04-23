# landform
This script uses random forest ML, observed landform data, and DEM-derived covariates to map landforms

The code is written in R. RF_landform_CGJ.Rmd is the source file. 

Input files
Raster data: All topographic indices (covariates) derived from 2m, 5m and 10m LiDAR DEMs. These datasets are named as:
2m model: r1_2m, r2_2m, ……… r8_2m
5m model: r1_5m, r2_5m, ……… r8_5m
10m model: r1_2m, r2_2m, ……… r8_2m
Vector data: observed landform data consisting of points (coordinates) with landform type and associated various covariate values as attributes.
