# WeatherPy with Python APIs

## Overview 
The goal is to use APIs keys to request data from OpenWeatherMap and Google Maps to create an application where users could input their weather preferences to filter the data for potential travel destinations and nearby hotels. 

## Resources
- Software: Jupyter Notebook 6.3.0, Python 3.7.10
- Library: Pandas, Numpy, CitiPy, Requests, Gmaps

## Data

### Retrieving Weather Data
- Generated a set of 2,000 random latitudes and longitudes
- Retrieved the nearest city name
- Lastly, performed an API call with OpenWeatherMap
Click [here](https://github.com/junepwk/world-weather-analysis/tree/main/weather_database) to view the weather database.

### Customer Travel Destinations Map
- Used input statements to retrieve customer weather preferences
- Used the preferences to filter and identify potential travel locations nd nearby hotels
- Displayed destinations on a marker layer map with pop-up markers
Click [here](https://github.com/junepwk/world-weather-analysis/tree/main/vacation_search) to view the code/resources used to create a customer travel destination map.

### Travel Itinerary Map
- Used Google Directions API to create a travel itinerary
- Displayed the route between cities 
- Created a marker layer map with pop-up marker for each city on the itinerary
Click [here](https://github.com/junepwk/world-weather-analysis/tree/main/vacation_itinerary) to view the code/resources used to create a travel itinerary map.
