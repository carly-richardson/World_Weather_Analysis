# WeatherPy with Python APIs
## Collect and analyze weather data across cities worldwide
### PlanMyTrip will use the data to recommend ideal hotels based on their clients' preferred weather preferences

- Retrieve the following information from the OpenWeather API call:
  - Latitude and longitude
  - Maximum temperature
  - Percent humidity
  - Percent cloudiness
  - Wind speed
  - Weather description (for example, clouds, fog, light rain, clear sky)

![image](https://user-images.githubusercontent.com/100643519/163726939-1ed6262e-1de1-4bd0-98d6-0ccd7cdc0773.png)

- Create a Customer Travel Destinations Map using the Google Maps Places API.
  - Input statements are written to prompt the customer for their minimum and maximum temperature preferences.
  - The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.
  - A marker layer map with pop-up markers for the cities has the following information:
    - Hotel name
    - City
    - Country
    - Current weather description with the maximum temperature

<img width="992" alt="WeatherPy_Vacation_map" src="https://user-images.githubusercontent.com/100643519/163727187-57a33386-e59e-4d8d-ac91-3728d526a875.png">

- Create a Travel Itinerary Map using the Google Maps Directions API.
  - A directions layer map with a pop-up marker for the cities on the itinerary is created. Each marker has the following information:
    - Hotel name
    - City
    - Country
    - Current weather description with the maximum temperature

<img width="677" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/100643519/163727413-9048e32f-7db3-4b46-b750-9e1d8f127deb.png">
<img width="694" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/100643519/163727425-861326ad-6119-4fa3-8987-77d7eeb9fedf.png">

### Resources
- Data Sources: WeatherPy_Database.csv, WeatherPy_vacation.csv
- Softwares: Python 3.9.10, Jupyter Notebook 6.4.5, OpenWeatherMap API, Google Cloud Platform
