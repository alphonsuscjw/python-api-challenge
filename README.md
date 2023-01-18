# python-api-challenge

This challenge is broken down into 2 deliverables, WeatherPy and VacationPy.

## WeatherPy
WeatherPy visualises the weather of over 500 cities of varying distances from the equator and creates a representative model of weather across cities of various latitude.

OpenWeatherMap API is used to retrieve weather data from the cities list generated randomly. Scatter plots are then created to showcase the following relationships:
1) Latitude vs. Temperature
2) Latitude vs. Humidity
3) Latitude vs. Cloudiness
4) Latitude vs. Wind Speed

The data frames and plots are then divided according to whether a city situates in the northen hemisphere or the southern hemisphere. Linear regression is done on the data of each hemisphere to see the relationships mentioned above.

Analysis of the linear regression shows that temperature has a stronger correlation with latitude than do humidity, cloudiness and wind speed.

## VacationPy
VacationPy utilises the geoViews Python library and the Geoapify API to choose future vacation spots.

The CSV file with the weather and coordinates data for each city created in WeatherPy is loaded. Then a map is displayed with all the cities as dots on it.

The cities are then narrowed down to those with my own ideal weather conditions. This gives around 20-30 cities. After that, a Geoapify API call is done to find the nearest hotel for each city. A map is displayed with all these cities as dots on it and with the hotel and country names in the hover message for each city.
