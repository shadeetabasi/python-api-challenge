# Python API Challenge: Weather & Vacation
This repository will house the Python API homework assignment due on January 5, 2020.

## Files and directories within this repository include:

### WeatherPy
* WeatherPy.ipynb
* cities.csv (Saved updated DataFrame housing new random assortment of cities)
* latvscloudinessplot.png
* latvshumidityplot.png
* latvstemperatureplot.png
* latvswindspeedplot.png
* northern_latvscloudiness_linearregression.png
* northern_latvshumidity_linearregression.png
* northern_latvsmaxtemp_linearregression.png
* northern_latvswindspeed_linearregression.png
* southern_latvscloudiness_linearregression.png
* southern_latvshumidity_linearregression.png
* southern_latvsmaxtemp_linearregression.png
* southern_latvswindspeed_linearregression.png
* weather_api_keys.py

### VacationPy
* VacationPy.ipynb
* hotel_marker.png
* humidity_heatmap.png
* PLEASE NOTE: API KEY FILE ON MY COMPUTER WAS NAMED g_api_keys.py. Not uploading to GitHub for best practices purposes.

### output_data
* cities.csv (original cities data file)

# Pymaceuticals : Assignment Details & Summary
[![Pymaceuticals](https://github.com/shadeetabasi/matplotlib-assignment/blob/main/Images/Laboratory.jpg)] = UPDATE

**Summary:** 
In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.
The first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude


**Observations (as seen within Jupyter Notebook):** 

* Overall, Capomulin appears to be effective in decreasing tumor volume over time. However, Ramicane appears to be associated with the smallest tumor volume/size out of four treatments - Capomulin, Ramicane, Infubinol, and Ceftamin.
* There appears to be one outlier in the Infubinol dataset - a mouse with a tumor volume below 36.83 - which would require further investigation.

![Pymaceuticalsboxplot](https://github.com/shadeetabasi/matplotlib-assignment/blob/main/Images/pymaceuticals_boxplot.png)

* There appears to be a positive correlation between mouse weight and tumor size - as indicateed in the final linear regression analysis conducted for the Capomulin drug regimen. This may indicate that either treatment was less effective in larger/overweight mice or simply that bigger mice have bigger tumors. We would need to look at change in tumor size over time for mice within different weight buckets to have a definitive answer here.

![Pymaceuticalslinearregression](https://github.com/shadeetabasi/matplotlib-assignment/blob/main/Images/pymaceuticals_linearregression.png)

