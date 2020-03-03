# SalgarCase

In this repository, we left the information used for the paper ** Reconstructing the 2015 Salgar flash flood using radar retrievals and a conceptual modeling framework in an ungauged basin** published at HESS. 
It contains the main code and the base data for all the analyses. 

## Code:
The code consists of three Jupyter notebooks that could be found in the **Code** folder.
01_Initial_setup.ipynb:  First attempt to extract the watershed from the DEM and DIR maps. Also, it includes the first configuration given to the model and previous results.
02_Watershed_simulation.ipynb: It contains the code of the second set of simulations and some other analysis.
03_Paper_figures.ipynb: Includes the code for almost all the figures and analysis done for the paper.

## Data:
The data folder is divided into four folders:

**rain**: contains the headers and binary rainfall for the modeling and analyses.
**raster**: It includes the **DEM** and **DIR** base rasters for the watershed setup.
**vector**: It has the network and boundary lines of the watershed.
**watershed**: Contains the **netCDF4** files used to hold the configuration of the watershed for the model WMF.

**Note**: To delineate, analyze, and model the watershed, we use the **WMF** (Watershed Modeling Framework) Python package (https://github.com/nicolas998/WMF).  

The article can be downloaded at:
*https://www.hydrol-earth-syst-sci-discuss.net/hess-2018-452/*
