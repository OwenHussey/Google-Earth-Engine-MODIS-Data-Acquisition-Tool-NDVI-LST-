# Google Earth Engine MODIS Data Acquisition Tools (NDVI + LST)
A repository containing links and instructions for the usage of two (2) Google Earth Engine applications. The applications use MODIS satellite imagery data in order to provide either Land Surface Temperature (LST) or Normalized Difference Vegetation Index (NDVI) data across a two year time span at a location of the users choice. 

Note: The LST application can provide both daily and 8-day average temperature values, while the NDVI application can only provide daily data values.

# Application Links:
Land Surface Temperature: https://owenhusseysjsu.users.earthengine.app/view/lst-2-year-span 

Normalized Difference Vegetation Index: https://owenhusseysjsu.users.earthengine.app/view/ndvi-data-tool

# Data:
The applications utilize MODIS satellite imagery data (approximately 1 km spatial resolution) from the following datasets:

Land Surface Temperature:

Normalized Difference Vegetation Index: https://developers.google.com/earth-engine/datasets/catalog/MODIS_MCD43A4_006_NDVI 

# Instructions:
1. Determine the type of data you need (LST or NDVI) and select the necessary application from the link list above. This should bring you to a window similar to the one below:
![image](https://github.com/OwenHussey/Google-Earth-Engine-MODIS-Data-Acquisition-Tool-NDVI-LST-/assets/149335707/e0836b38-d57d-49af-b107-de5cbd226487)
Note the "Search Places" bar and data availability range at the top of the interface, as well as the "Input Start Date" bar and dropdown menu in the lower-left corner.

2. Determine what time range you need data for, and input an appropriate starting date (yyyy-mm-dd) into the "Input Start Date" bar. Both applications will gather data for the two years AFTER the chosen starting date. For example, if you set the starting date as 2020-01-01 (January 1st, 2020), the data gathered will represent 2020-01-01 to 2021-12-31 (December 31st, 2021). Be sure that the chosen data range is within the confines of the data range at the top of the interface.

	If using the LST application, use the dropdown menu in the lower-left corner to choose either daily LST data or 8-day average LST data. If using the NDVI application, only daily data will be available.

3. Using either the "Search Places" bar at the top of the interface or manual navigation, find your desired study site. Once the location is found, simply click where you would like to extract LST/NDVI data from. This will generate a graph in the lower-right corner of the screen, as well as generate a color gradient over the map. Each click will generate a new graph/color gradient, which will contain data of their respective locations.
![image](https://github.com/OwenHussey/Google-Earth-Engine-MODIS-Data-Acquisition-Tool-NDVI-LST-/assets/149335707/970f9070-36f6-400f-a30a-f1195a446ced)
	The data charts cannot be removed from the interface once generated, so if more charts are needed, you will need to refresh the applciation page and re-enter your start date and location.

	Note: Daily data takes considerably more time to load/generate than 8-day average, so be patient!

5. For each generated graph, you can also download the data table as a .csv file containing all of the LST/NDVI data for that location. To do this, click on the small icon in the upper-right corner of the graph you want the data from.
![image](https://github.com/OwenHussey/Google-Earth-Engine-MODIS-Data-Acquisition-Tool-NDVI-LST-/assets/149335707/32f0889b-081d-48b1-97d7-fdb30608a848)
This will open up a new window with a fullscreen view of the graph. This makes it much easier to see individual points. To download the .csv file, click on the "Download CSV" button in the upper-right corner of the graph window. This will download the data table as a .csv file!
![image](https://github.com/OwenHussey/Google-Earth-Engine-MODIS-Data-Acquisition-Tool-NDVI-LST-/assets/149335707/2005eb84-e46b-4689-984f-5ca3c89c95ea)





