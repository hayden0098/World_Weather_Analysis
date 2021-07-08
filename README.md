# World_Weather_Analysis

## Review:
In this project of analysis, we use analysis, visualization, and statistical skills, API data retrieval by retrieving and analyzing weather data and map data from OpenWeatherMap and Google API for a travel company, PlanMyTrip. Successfully completing the tasks will be using Python, decision and repetition statements, data structures, Pandas, Matplotlib, and SciPy statistics. At the end the code be able to use input statements from the beta tester to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## 
From 2000 random latitudes and longitudes get the nearest city and Retrieve all of the following information from the API call:
* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Weather description (for example, clouds, fog, light rain, clear sky) 
![current-weather-description]()

Prompt user input their minimum and maximum temperature criteria for their vacation and filter the cities then retrieve hotel names from API call

![completed-where-hotels-are-found]()

Generate the marker layer map that will have opo-up markers for each city on the map. Each marker has the following information:
* Hotel name
* City
* Country
* Current weather description with the maximum temperature

Then Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

![direction]()  ![travel_map_markers]()
