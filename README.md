# World_Weather_Analysis

## Background
Created Jupyter Notebook scripts that search for locations based on weather parameters, find hotel near each location, and allow for creation of route maps around selected location.

Background
Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.



## Results

## Summary



bernardo
World_Weather_Analysis
World_Weather_Analysis analysis files: WeatherPy.ipynb | VacationPy.ipynb

Purpose
The purpose of the challenge, given that we worked at a Travelpy, a company that creates or proposed your vacation based on the weather preference of the clients, was to create a vacation map that allows use insert their weather preferences to identify potential vacation destinations. For this, we used Google Api's. We also provide the user with recommended ideal hotels with three proffered travel destinations ##Overview To create the vacation map, we generated a list of 1,500 random latitudes and longitudes. With the coordinates, we retrieved and compiled a list of the nearest cities using the city module. Then, we used the OpenWeatherMap API to request the current weather data from each unique town on the list. The resulting map provides users with descriptions of the destinations found on our list, including hotel name, city, country, and current weather and description. To create a vacation map, We made a list of 1,500 random latitudes and longitudes. With the coordinates, we compiled a list of the nearest cities using citipy module, using the OpenWeatherMap API to extract the weather data from each unique town on the list. The map provides used hotel information based on the weather specification they asked for.

Challenge
Vacation_Seach| Vacation_Itinerary

The challenge consisted of creating an itinerary for someone's vacation, so (they)had to choose their weather preference, and we would show them on a map all of the hotel possibilities. Finally, we had to create two maps, one with the cities in the itineraries and another with the route.