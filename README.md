# World_Weather_Analysis
Module 6: WeatherPy with Python APIs
## Overview
Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data I’ve already retrieved in this module. Then, I'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, I will create a travel route between the four cities as well as a marker layer map.

### Weather Data
Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data I gathered in this module, I use my API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.



### Customer Travel Destinations Map
I use input statements to retrieve customer weather preferences, then I use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/90117562/154835598-16b66c66-af8e-4793-80a7-66220ce0d511.png)


### Travel Itinerary Map
I use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, I create a marker layer map with a pop-up marker for each city on the itinerary.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/90117562/154835599-e84ef893-3a7f-4905-8cbb-efe1b9b4e4a8.png)
