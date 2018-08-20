# gis-workshop

This Rstudio project contains everything you need for the **Intro to GIS in R workshop**


## Data sources:

- ### `csv/salamander_mol.csv`:  
    Spatially located genetic data adapted from: _Tracking climate change in a dispersal‐limited species: reduced spatial and genetic connectivity in a montane salamander <https://doi.org/10.1111/mec.12310>_  


- ### `raster/worldclim_30s/`:
    Subsamples cropped from 30s WorldClim 1.4 (current conditions) data available from <http://worldclim.org/current> for bioclimatic variables:
    + **BIO4 = Temperature Seasonality (standard deviation \*100)**  
    + **BIO5 = Max Temperature of Warmest Month**  
    + **BIO6 = Min Temperature of Coldest Month**  
    + **BIO15 = Precipitation Seasonality (Coefficient of Variation)**  

- ### `raster/worldclim_10m/`:
    10min WorldClim 1.4 (current conditions) data sourced from <http://worldclim.org/current> for bioclimatic variable:
    + **BIO1 = Annual Mean Temperature**


- ### `raster/MEX_msk_cov/`:
   Land cover data for Mexico sourced as a country mask through the **DIVA-GIS Download data by country** portal at <http://www.diva-gis.org/gdata>.  
   Original data source: _Global Land Cover 2000 database. European Commission, Joint Research Centre, 2003, <http://forobs.jrc.ec.europa.eu/products/glc2000/glc2000.php>_. 
   
---

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />WorldClim 1.4 (current conditions) by www.worldclim.org; Hijmans et al., 2005. Int. J. of Clim. 25: 1965-1978 is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.