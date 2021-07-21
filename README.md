# World_Weather_Analysis
## Overview
Help with the PlanMyTrip beta:

  [Deliverable 1:](https://github.com/jzebker/World_Weather_Analysis/tree/main/weather_database) Create a new DataFrame with the weather description added to the weather data you’ve already retrieved.
  
  [Deliverable 2:](https://github.com/jzebker/World_Weather_Analysis/tree/main/vacation_search) Have the beta testers use input statements to filter the data for their weather preferences and use these preferences to identify potential travel destinations and nearby hotels.
  
  [Deliverable 3:](https://github.com/jzebker/World_Weather_Analysis/blob/main/vacation_itinerary/WeatherPy_travel_map_markers.png) Have the beta tester choose four cities to create a travel itinerary and, using the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.
  
## [Deliverable 1](https://github.com/jzebker/World_Weather_Analysis/tree/main/weather_database)
<p align="center">
  <img width="716" alt="deliverable1" src="https://user-images.githubusercontent.com/84994321/126562427-b5815dd6-42dd-4031-94df-aea1952d90de.png">
</p>

***Notes***: 

• uses CitiPy to find the closest city to each set of coordinates in an array of 2,000 randomly generated latitudes and longitudes

• retrieves data with OpenWeatherMap API (http://api.openweathermap.org)

## [Deliverable 2](https://github.com/jzebker/World_Weather_Analysis/tree/main/vacation_search)
<p align="center">
  <img width="716" alt="deliverable1" src="https://user-images.githubusercontent.com/84994321/126563604-3ecf0645-4a0f-4f41-a40d-da96aa25fd75.png">
</p>

***Notes***: 

• filters data by user input for desired maximum temperature in °F

• uses Maps API Nearby Search (https://maps.googleapis.com/maps/api/place/nearbysearch/) and adds the most [prominent](https://github.com/jzebker/World_Weather_Analysis/blob/main/readme_pics/hotel_method.png) hotel within the given radius

## [Deliverable 3](https://github.com/jzebker/World_Weather_Analysis/blob/main/vacation_itinerary/WeatherPy_travel_map_markers.png)
<p align="center">
  <img width="1005" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/84994321/126565747-dda9369c-e651-4d6a-b9f3-d5c65e807f05.png">
</p>

***Notes***: 

• after choosing 4 geographically close cities, uses Directions API (https://developers.google.com/maps/documentation/directions/overview) to find route between them

• cities must have a route between them, for example, maps was unable to find directions in New Caledonia 
