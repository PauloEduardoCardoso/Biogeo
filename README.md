Envelope Model
=============

![](https://cloud.githubusercontent.com/assets/173906/4108389/99dbc590-31d6-11e4-9651-943875814e55.png)

Model species distribution with Bioclim envelope method using bioclimatic data from [Worldclim](http://www.worldclim.org/bioclim) and SRTM DEM.

###Bioclim varibles:

- BIO1 = Annual Mean Temperature  
- BIO2 = Mean Diurnal Range (Mean of monthly (max temp - min temp))  
- BIO3 = Isothermality (BIO2/BIO7) (* 100)  
- BIO4 = Temperature Seasonality (standard deviation *100)  
- BIO5 = Max Temperature of Warmest Month  
- BIO6 = Min Temperature of Coldest Month  
- BIO7 = Temperature Annual Range (BIO5-BIO6)  
- BIO8 = Mean Temperature of Wettest Quarter  
- BIO9 = Mean Temperature of Driest Quarter  
- BIO10 = Mean Temperature of Warmest Quarter  
- BIO11 = Mean Temperature of Coldest Quarter  
- BIO12 = Annual Precipitation  
- BIO13 = Precipitation of Wettest Month  
- BIO14 = Precipitation of Driest Month  
- BIO15 = Precipitation Seasonality (Coefficient of Variation)  
- BIO16 = Precipitation of Wettest Quarter  
- BIO17 = Precipitation of Driest Quarter  
- BIO18 = Precipitation of Warmest Quarter  
- BIO19 = Precipitation of Coldest Quarter  

Plot resulting raster model using `ggplot2::ggplot`
