# sudo-grow-hackathon
Sudo Grow Hackathon Challenge Problems

## CHALLENGE 1
**Summary:** KisanHub has around 100 Davis weather stations deployed around the UK. Weather data is used to provide insight into everything from irrigation scheduling to forecasting yield. 

**Task:** Use the weather station API to build services that overlay on a mapping interface to visualise the data, provide regional trends to optimise decision making. 

**Data Provided:** KisanHub will provide API access to these data sets and locations of where the stations have been deployed.

**API Documentation:** Please visit [https://developer.kisanhub.com/](https://developer.kisanhub.com/) and check API documentation under Weather Data category. Weather data is available from our met micro service. For this exercise we will be making 26 weather stations available for query exposing 1 months data at 15mins interval.

**Assistance:** 
- One of the KisanHub team will be available to help with any questions. 
- Kindly send an email to sudo.challenge@kisanhub.com to request your API token.

## CHALLENGE 2

**Summary:** Vegetation indices are commonly used as an indicator for crop health. These are typically derived from satellites with image in the visible and near-infrared parts of the spectrum. The biggest drawback of using this slice of the light spectrum is it's susceptibility to clouds. RADAR operates in a slice of the light spectrum unaffected by atmospheric conditions, and so will always be able to obtain a reading.

**Task:** This task would involve taking RADAR data, from Sentinel1, the first in a series of EO missions by ESA, and mapping it on to vegetative indices derived from Sentinel2. The goal is to investigate whether any correlation exists between RADAR backscatter and vegetation intensity. 

**Satellite Data:** 

https://earth.esa.int/web/sentinel/user-guides/

Sentinel 1: https://www.esa.int/Our_Activities/Observing_the_Earth/Copernicus/Sentinel-1/Instrument

Sentinel 2: https://www.esa.int/Our_Activities/Observing_the_Earth/Copernicus/Sentinel-2/Instrument


**Vegetation Index:** 
The NDVI is calculated from these individual measurements as follows:

NDVI = (NearInfraRedBand — RedBand)/(NearInfraRedBand + RedBand)

**Soil Moisture Index:** 
The NDWI is calculated from these individual measurements as follows:

NDWI = ( NearInfraRedBand – ShortWaveInfraRed ) / ( NearInfraRedBand + ShortWaveInfraRed )


**Data Provided:** Access will be available to the public satellite agencies to download imagery.  

**Assistance:** 
- One of the KisanHub team will be available to help with any questions. 
- Harshal Galgale will be available at the Hackathon to provide this data. 
