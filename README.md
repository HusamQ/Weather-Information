# Module-6-Challenge
This prject to demostrates weather information for in the world based on auto-generated latitude and longitude for a vacation planner. I parse the generated longitude and latitude to get relevant information about the corresponding location. 

By making API calls, I retreived the weather data such as minimum tempreture, maximum tempreture, weather description along with the city name and nearest hotel. 

# Data sample and collection
- Randomly generated a 2000 float number for each langitude and latitude and then pair them together to pin point a location on earth. 
- Retrieve weather information by calling OpenWeatherMap call. 
- Store the data into a csv file. 

# Customer Travel Destination
-By asking the user to enter their weather preference to return a potential travel destination and nearby hotels. 
- Save custom data into a new csv file.
-Show the user each location with markers for each city and display the hotel name, city and tempreture in an integrated map by calling Google maps API.


#Travel itinerary
-Based on the user's weather preference, four DataFrames are created, one for each city on the itinerary (data is loaded from the custom csv file.
-The latitude and longitude pairs for each of the four cities are retrieved.
- A directions layer map between the cities and the travel map is created.
- A marker layer map with a pop-up marker for the cities on the itinerary is created.
