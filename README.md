# GRAD521_QuigleyDMP_2026
## Data Description

The first dataset is a spreadsheet of observations from known golden eagle nesting areas and will include all historic surveys as well as current surveys. This spreadsheet includes nest IDs, nest locations, occupancy status (eagle presence), and reproductive outcome (success, # chicks fledged). This data will be collected by field technicians visiting nest sites multiple times per breeding season and entering observations in ESRI Field Maps form. The observations in Field Maps are synced to Arc GIS Online server and will be downloaded and saved as CSV files and compiled by year.

The second dataset is a collection of GPS data points from 25 individually marked eagles in the northeast Oregon study area. This data is collected via MTI GPS/UHF solar-charged backpack transmitters that are placed on captured eagles. The transmitters upload the data to ARGOS satellites, from which location data can be downloaded as a CSV for each transmitter. I will combine and process all CSVs to project location data as shapefiles in ESRI ArcPro software to model home range characteristics of breeding eagles in Oregon.

The third dataset is a spreadsheet of remote sensed environmental data collected from publicly available resources including MODIS, TerraClimate, and Landsat. The raster files are pulled from publicly available resources, clipped to the home range of a nesting golden eagle (modeled above) around each nest site, and averaged over the appropriate area and timeframe to result in a numerical value representing primary production (NDVI), drought (PDSI), proportion of landscape burned, and proportion of developed land. This data will be linked to each individual nest ID from the previous dataset. This data will be sourced and processed by utilizing Google Earth Engine before downloading CSV files and compiling data by nest ID and year.

## Project Goals

While golden eagle (Aquila chrysaetos) population trends and occupancy status are stable or slightly decreasing across their entire range, this information is not known for the population of eagles that inhabit Eastern Oregon. I am using a historic data set (2011-2020) to model eagle occupancy and reproductive rates across Eastern Oregon to evaluate correlations with landscape scale environmental factors including primary production, drought, fire, and human development. Concurrently we are collecting data in the four northeast counties (Umatilla, Union, Baker, Wallowa) in order to evaluate the ability of the occupancy and productivity models to predict population status within that region.

## Hypotheses

Golden eagle occupancy and production is negatively correlated with decreased primary production and increased drought. Golden eagle occupancy and production is negatively correlated with increased human development, especially as it relates to energy infrastructure.
