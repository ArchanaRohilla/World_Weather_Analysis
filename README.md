# World Weather Analysis 
Weather Analysis and building of a travel app for customers of 600+ cities around the world.

## Project Overview
In this project, a travel app for customers is built using weather data of 600+ cities along with the data to recommend ideal hotels based on clients’ weather preferences.

## Tools
Python, citipy, Pandas, Matplotlib, SciPy, Google Maps API, Google Places API, OpenWeatherMap API, Jupyter Notebook

## Summary
- The Travel App allows customers to search for locations they want to travel based on their temperature preferences.

![alt text](image/map_markers.png)

Your clients will enter their preferences. Your code will tell them where to travel.

Now that we have all the cities the customer wants to travel to, they will need to find a hotel to stay in the city

Once the customers have filtered the database (DataFrame) based on their temperature preferences, show them a heatmap for the maximum temperature for the filtered cities. In addition, create a marker for each city that will display the name of the city, country code, maximum temperature, and name of a nearby hotel within three miles of the coordinates when the marker is clicked.
A weather description to the pop-up markers for customers so that they know what the weather is as they are traveling
A notation in the search criteria to indicate if it is raining or snowing for customers who are making travel decisions in real-time
A map that shows the directions for customers’ travel itinerary
For the new modifications to the PlanMyTrip app, you are asked to add more data to the database, or cities DataFrame, so that customers know the weather in the cities when they click on a pop-up marker. You’ll also need to add the amount of rainfall or snowfall within the last three hours so that customers can filter the DataFrame using input statements based on the temperature range and whether or not it is raining or snowing. Finally, you’ll need to create a directions layer Google map that shows the directions between multiple cities for travel.



![alt text](image/WeatherPy_vacation_map.png)


![alt text](image/WeatherPy_travel_map.png)


![alt text](image/WeatherPy_travel_map_markers.png)
