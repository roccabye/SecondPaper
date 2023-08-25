# SecondPaper
Hydrological Analysis
Description: 
I recommend first performing GIS Routing ( that will give you mask file (NLDAS grid points to work with generating the essential data)) 
Creating Forcing Files:
Requires the study region csv file (description of lat lon on NLDAS 1/16th grid -  best if use the mask file created in the GIS routing)
Otherwise: download the HUC03 region shapefile and NLDAS 1/16th grid data
Clip the NLDAS to HUC03 region and generate HUC03.csv file

- involves three forcing files
  1. Meteorological Forcing
  2. vegetation Files
  3. Soil Parameter Files
Running VIC Model (in parallel mode and individula mode)
Running Routing
Creating Streamflow output
plotting them

