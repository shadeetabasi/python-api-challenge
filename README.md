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
* PLEASE NOTE: API KEY FILE ON MY COMPUTER WAS NAMED g_api_keys.py. The file in this folder is not updated with my g key for security purposes.

### output_data
* cities.csv (original cities data file)

### ReadME Images
* equatorsign.png
* heatmap.png

# Weather Assignment Details & Summary
![WeatherPy](https://github.com/shadeetabasi/python-api-challenge/blob/main/ReadME_Images/equatorsign.png)

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

* There does not appear to be an overt relationship between latitude and cloudiness or latitude and wind speed.

![latvscloudiness](https://github.com/shadeetabasi/python-api-challenge/blob/main/WeatherPy/latvscloudinessplot.png)
![latvswindspeed](https://github.com/shadeetabasi/python-api-challenge/blob/main/WeatherPy/latvswindspeedplot.png)

* While the northen hemisphere appears to have negative correlation with max temperature (F) - meaning that the farther away from the equater, the colder it gets, the southern hemisphere has a positive correlation with max temperature, meaning the opposite. This indicates that the the closer a city is to the equater, the higher the max temperature would likely be.

![northernhemispheremaxtemp](https://github.com/shadeetabasi/python-api-challenge/blob/main/WeatherPy/northern_latvsmaxtemp_linearregression.png)
![southernhemispheremaxtemp](https://github.com/shadeetabasi/python-api-challenge/blob/main/WeatherPy/southern_latvsmaxtemp_linearregression.png)

* In the northern hemisphere, wind speeds(mph) have a positive correlation with latitude, meaning that the farther away from the equater and higher the latitude, the greater the wind speeds. Conversely, the southern hemisphere shows a negative correlation between latitude and wind speeds, which means that the lower the latitude and farther away from the equater, the higher the wind speeds.

![northernwindspeed](https://github.com/shadeetabasi/python-api-challenge/blob/main/WeatherPy/northern_latvswindspeed_linearregression.png)
![southernwindspeed](https://github.com/shadeetabasi/python-api-challenge/blob/main/WeatherPy/southern_latvswindspeed_linearregression.png)

# Vacation Assignment Details & Summary
![VacationPy](https://github.com/shadeetabasi/python-api-challenge/blob/main/ReadME_Images/heatmap.png)

**Summary:** 
To complete this part of the assignment,you will need to do the following:
* Create a heat map that displays the humidity for every city from Part I.
* Narrow down the DataFrame to find your ideal weather condition. For example:
** A max temperature lower than 80 degrees but higher than 70.
** Wind speed less than 10 mph.
** Zero cloudiness.
* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
* Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

**Observations (as seen within Jupyter Notebook):** 
* See below for a heatmap of the locations within my random selection of cities that fit the above "perfect weather conditions".
![humidityheatmap](https://github.com/shadeetabasi/python-api-challenge/blob/main/VacationPy/humidity_heatmap.png)

* See below for an overlay of the above map to include markers including the hotel name, city and country for places that not only have perfect weather conditions, but also a hotel within 5,000 meters.
![hotelmarker](https://github.com/shadeetabasi/python-api-challenge/blob/main/VacationPy/weather_hotel_marker_heatmap_final.png)