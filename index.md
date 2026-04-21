# Data Description
While golden eagle (*Aquila chrysaetos*) population trends and occupancy status are stable or slightly decreasing across their entire range, this information is not known for the population of eagles that inhabit Eastern Oregon. I am using a historic data set (2011-2020) to model eagle occupancy and reproductive rates across Eastern Oregon to evaluate correlations with landscape scale environmental factors including primary production, drought, fire, and human development. Concurrently we are collecting data in the four northeast counties (Umatilla, Union, Baker, Wallowa) in order to evaluate the ability of the occupancy and productivity models to predict population status within that region.

The first dataset is a spreadsheet of observations from known golden eagle nesting areas and will include all historic surveys as well as current surveys. This spreadsheet includes nest IDs, nest locations, occupancy status (eagle presence), and reproductive outcome (success, # chicks fledged). This data will be collected by field technicians visiting nest sites multiple times per breeding season and entering observations in ESRI Field Maps form. The observations in Field Maps are synced to Arc GIS Online server and will be downloaded and saved as CSV files and compiled by year.

The second dataset is a collection of GPS data points from 25 individually marked eagles in the northeast Oregon study area. This data is collected via MTI GPS/UHF solar-charged backpack transmitters that are placed on captured eagles. The transmitters upload the data to ARGOS satellites, from which location data can be downloaded as a CSV for each transmitter. I will combine and process all CSVs to project location data as shapefiles in ESRI ArcPro software to model home range characteristics of breeding eagles in Oregon.

The third dataset is a spreadsheet of remote sensed environmental data collected from publicly available resources including MODIS, TerraClimate, and Landsat. The raster files are pulled from publicly available resources, clipped to the home range of a nesting golden eagle (modeled above) around each nest site, and averaged over the appropriate area and timeframe to result in a numerical value representing primary production (NDVI), drought (PDSI), proportion of landscape burned, and proportion of developed land. This data will be linked to each individual nest ID from the previous dataset. This data will be sourced and processed by utilizing Google Earth Engine before downloading CSV files and compiling data by nest ID and year.

Golden Eagle Nest Data – 1-2 GB

Golden Eagle GPS Data – 2-5 GB

Remote Sensed Environmental Data – 1-2 GB

# Roles and Responsibilities
DMP Implementation – It is the responsibility of the PI and the graduate student to implement the DMP and to coordinate roles and responsibilities of outside collaborators and staff.

Data collection/generation – All current data collection efforts are a combined effort by departmental (Oregon Department of Fish & Wildlife) staff and volunteers on ESRI Field Maps software, on pre-generated data sheets. Previous data collection and generation was completed by staff and volunteers on paper datasheets and transferred to an Excel spreadsheet. The graduate student will gather data generated from publicly available remote sensed databases. Finally, departmental database manager will automatically download GPS data from ARGOS satellite systems and parse through MTI software.

Data management/organization/quality control/metadata generation/data analysis – It is the graduate student’s responsibility to ensure all current and past data is organized and checked for errors. The student will generate metadata for each data source above. The graduate student is responsible for organization, naming, and version control of all original files and any products of data analysis. All analysis will be the responsibility of the PI and graduate student. Organization of department GPS database will be the responsibility of the database manager.

Software maintenance – The graduate student is responsible for making sure all data collection software and applications, including maintaining Field Maps data collection form, are up to date and available for data collection. Department staff are responsible for database management and software/server maintenance.

Sensitive data protection – It is the role of the department (ODFW) to manage and protect any sensitive data, including protected species location data.

Archiving & preservation – The department is responsible for archiving and preserving all data created and used in the research project.

If anyone responsible for data management were to leave, the department would take over any necessary roles and responsibilities left vacant.

The research is funded by the U.S. Fish and Wildlife Service through a Pittman-Robertson Act grant and therefore all data, excluding sensitive data, must be shared via publicly available federal databases. All data must also be retained for 2 to 5 years following the completion of the grant.

During the project, original copies of field and remote sensed data will be collected and stored on ESRI and Google Earth Engine cloud systems, respectively. All field (historic and current) and remote sensed data will be collected, compiled, and stored on the graduate student’s local hard drive. GPS location data will be automatically downloaded and stored in departmental database, accessible via shared network drive.

All field data from the graduate student’s local hard drive will be manually backed up on departmental shared network drive on a weekly basis. In total the data will be located in three separate places, ESRI/Google cloud systems, local hard drive, and department shared network drive. The GPS location data is automatically downloaded from ARGOS cloud system, which maintains a record of all locations upon request. In total GPS location data will have copies in two locations, ARGOS cloud system and department shared network drive. The department shared network is maintained and backed up by professional staff to ensure no data is lost. 

# Data Standards and Metadata
# Storage and Security
# Access and Data Sharing
# Archiving and Preservation
