# Weather Analysis and Ideal Vacation Locations

- **Weather Analysis:** [`WeatherPy`](WeatherPy/WeatherPy.ipynb) Using a Python script and API, the weather of randomly selected 500+ cities was obtained to visualize the varying distance from the equator from across the world. Both (https://pypi.python.org/pypi/citipy) and [OpenWeatherMap API](https://openweathermap.org/api) were used to create a visual representative model of weather across world cities.

A series of scatter plots were created to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Linear regressions were run on each relationship, only this time they were separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

- **Vacation Locations:** [`VacationPy`](VacationPy/VacationPy.ipynb) Jupyter-gmaps and the Google Places API were used to create a heat map that displays the humidity for every city from the previous project (WeatherPy) based on latitude and longitude.
- Personal ideal weather conditions for a vacation were used to narrow down the list of cities. 
- Using Google Places AP, a hotel for each city located within 5000 meters of the city were listed.

The hotels were plotted on top of the humidity heatmap.
=======

