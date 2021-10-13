# WeatherPy with Python APIs


**Table of Contents**
  <ol>
    <li>
      <a href="#overview">Overview</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href="#retrieving-weather-data">Retrieving Weather Data</a></li>
        <li><a href="#customer-travel-destinations-map">Customer Travel Destinations Map</a></li>
        <li><a href="#travel-itinerary-map">Travel Itinerary Map</a></li>
      </ul>
    </li>
  </ol>


## Overview 
The goal was to use APIs keys to request data from OpenWeatherMap and Google Maps to create an application where users could input their weather preferences to filter the data for potential travel destinations and nearby hotels. 

## Getting Started
<details>
<summary>Resources</summary>
  
* Data Sources: 
    * [weatherpy_database.csv](https://github.com/junepwk/World-Weather-Analysis/blob/main/weather_database/weatherpy_database.csv)
    * [weatherpy_vacation.csv](https://github.com/junepwk/World-Weather-Analysis/blob/main/vacation_search/weatherpy_vacation.csv)
* Softwares: 
    * Jupyter Notebook 6.3.0
    * Python 3.7.10
- Libraries: 
    - Pandas
    - Numpy
    - Matplotlib
    - Datetime
    - [CitiPy](https://github.com/wingchen/citipy)
    - [Requests](https://requests.kennethreitz.org/en/master/)
- Tools:
    - [OpenWeatherMap API](https://openweathermap.org/api)
    - [Gmap API](https://mapsplatform.google.com/)
</details>

### Prerequisites
* Go to the [Citipy](https://github.com/wingchen/citipy) repo for further details and how it can be used. 
  ```
  pip install citipy
  ```
* Go to the [Requests](https://requests.kennethreitz.org/en/master/) document for more information.
  ```
  import requests
  requests.__version__
  ```
   ###### **Note**: The output should be version 2.22.0 or later.


### Installation 

**OpenWeatherMap API**
  1. Get a free API Key at [OpenWeatherMap API](https://openweathermap.org/api)
  2. Click "sign up" and create an account.
  3. Sign in and click on "API keys"
  4. Enter your API in ```config.py```
     ```
     weather_api_key = "ENTER YOUR API"
     ```
       
**Gmap API**
  1. Navigate to [Gmap API](https://mapsplatform.google.com/)
  2. Click on "Get Started"
  3. Check the "Maps" and "Places" boxes, and then click "Continue"
  4. After setting up your account, add your API in ```config.py```
     ```
     g_key = "ENTER YOUR API"
     ```

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage

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

