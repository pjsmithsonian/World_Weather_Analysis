# World_Weather_Analysis

## Overview 

### Purpose
For the PlanMyTrip app we are gathering necessary data points to assist travelers. There are 3 main deliverables for this assignment.



### Weather Data Retrieval
The first deliverable is to get all of the data to be used in the deliverables 2 and 3. This is the generation of 2000 latitude and longitude coordinates, getting the weather data for the nearest cities and saving this data to a CSV file for the other deliverables.

### Customer Travel Destinations Map
Reading in the weather data from deliverable 1, we are taking the analysis a step further to get desired temperature ranges from the user and narrowing down the results accordingly. With the additional information, we are also finding hotels for these more optimal locations. From there we are mapping these locations using the Google GMAPS API and exporting to a CSV file.

![Vacation_Map](/Vacation_Search/WeatherPy_vacation_map.PNG)

### Travel Itinerary Map
Using the narrowed down locations provided from deliverable 2, we are creating a travel itinerary for locations that are within the same country. We ultimately provide the route to be traveled and additional data with markers.
 
![Travel_map](/Vacation_Itinerary/WeatherPy_travel_map.PNG)