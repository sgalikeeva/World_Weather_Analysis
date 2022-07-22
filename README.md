# World Weather Analysis: 

## Overview
The objective is to create a travel itinerary map based on customer weather preferences for a trip. 

## Results

To start off weather data was retrieved via an API call to OpenWeatherMap. The data included latitude, longitude, maximum temperature, percent humidity, percent cloudiness, wind speed and weather description. This data was added to a dataframe and then exported to a csv. Next, a map is created of possible destinations for the customer. Two input statements are created that prompt the user to enter their minimum and maximum temperature criteria for their vacation. The map is based on customer weather preferences via the input statements. Based on those preferences, potential travel destinations and nearby hotels were identified, retrieved from data via an API call to Google Maps. The destinations are shown on a marker layer map with pop-up markers.

[!This is an image](Vacation_Search/WeatherPy_vacation_map.png)

From the vacation map, a travel itinerary map is created between 4 chosen cities for a customer. The cities chosen are Innisfail, Yulara, Ulladulla and Sawtell in Australia. The Google Directions API was used to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. 

[!This is an image](Vacation_Itinerary/WeatherPy_travel_map.png)

A marker layer map was created with a pop-up marker for each city on the itinerary.

[!This is an image](Vacation_Itinerary/WeatherPy_travel_map_markers.png)
