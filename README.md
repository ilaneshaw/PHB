# PHB

## PHB.Rmd
This is the core of the post-hoc binning procedure. Here the following is carried out:
1) Setup of folders and library 
2) Input of data - raster files of Boreal Avian Modelling (BAM) Project national models of predicted bird density, study area shapefile, rasterToMatch (LCC05), categorical raster of land class, categorical raster of forest class, age raster of areas covered by forest class raster.
3) Extraction of raster data into birdDatasets
4) 1D post-hoc binning (prediction of bird density by land/forest class), and associated data exploration and analysis
5) 2D post-hoc binning (prediction of bird density by forest and age class), and associated data exploration and analysis
6) Comparison of 1D and 2D binning

## MB.Rmd
This is a secondary section, to be used once PHB.Rmd has been run. Here the following is carried out:
1) Rasters of predicted bird density (mapBins) are produced according to the categorical predictions made in 1D and 2D post-hoc bining
2) Rasters showing residuals of mapBins rasters and BAM national model rasters are produced
3) Code to visually present and compare these rasters is provided
4) Analysis and comparison of 1D and 2D binning

## dataExploration.Rmd
Here the input landscape data is explored, and summary statistics and graphs of the data are produced.  
