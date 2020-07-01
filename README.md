# Assessing differences in plant sampling biases
## Introduction
This projects aims to quantify the differences in the sampling
of vouchered plant specimens vs. observations-only plant
specimens.
To quantify sampling biases:
```r
library(phyloregion)
plot_swatch(pts$poly_shp, values = pts$poly_shp$richness, k=30)

######### Arguments #######################
# x: A raster file of the environmental variable
# y: Spatial polygons corresponding to the study area to extract the variable.
# val: String to rename the column with the extracted variable.
# FUN: The function to summarize the values (e.g. sd, mean)
```
