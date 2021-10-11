# WeatherPy with Python APIs

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#overview">Overview</a>
    </li>
    <li>
      <a href="#resources">Resources</a>
    </li>
    <li>
      <a href="#data">Data</a>
      <ul>
        <li><a href="#retrieving-weather-data">Retrieving Weather Data</a></li>
        <li><a href="#customer-travel-destinations-map">Customer Travel Destinations Map</a></li>
        <li><a href="#travel-itinerary-map">Travel Itinerary Map</a></li>
      </ul>
    </li>
  </ol>
</details>

## Overview 
The goal was to use APIs keys to request data from OpenWeatherMap and Google Maps to create an application where users could input their weather preferences to filter the data for potential travel destinations and nearby hotels. 

## Resources
- Data Source: weatherpy_database.csv, weatherpy_vacation.csv
- Software: 
    - Jupyter Notebook 6.3.0
    - Python 3.7.10
- Library: 
    - Pandas
    - Numpy
    - [CitiPy](https://github.com/wingchen/citipy)
    - [Requests](https://requests.kennethreitz.org/en/master/)
- Tool:
    - [OpenWeatherMap API](https://openweathermap.org/api)
    - [Gmap API](https://mapsplatform.google.com/)


<p align="right">(<a href="#top">back to top</a>)</p>

## Data

### Retrieving Weather Data
- Generated a set of 2,000 random latitudes and longitudes
- Retrieved the nearest city name
- Lastly, performed an API call with OpenWeatherMap

Click [here](https://github.com/junepwk/world-weather-analysis/tree/main/weather_database) to view the weather database.


<p align="right">(<a href="#top">back to top</a>)</p>

### Customer Travel Destinations Map
- Used input statements to retrieve customer weather preferences
- Used the preferences to filter and identify potential travel locations nd nearby hotels
- Displayed destinations on a marker layer map with pop-up markers

Click [here](https://github.com/junepwk/world-weather-analysis/tree/main/vacation_search) to view the code/resources used to create a customer travel destination map.

![weatherpy_vacation_map](https://github.com/junepwk/world-weather-analysis/blob/main/vacation_search/weatherpy_vacation_map.png)


<p align="right">(<a href="#top">back to top</a>)</p>

### Travel Itinerary Map
- Used Google Directions API to create a travel itinerary
- Displayed the route between cities 
- Created a marker layer map with pop-up marker for each city on the itinerary

Click [here](https://github.com/junepwk/world-weather-analysis/tree/main/vacation_itinerary) to view the code/resources used to create a travel itinerary map.

![weatherpy_travel_map](https://github.com/junepwk/world-weather-analysis/blob/main/vacation_itinerary/weatherpy_travel_map.png)


<p align="right">(<a href="#top">back to top</a>)</p>

