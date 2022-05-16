# World_Weather_Analysis

## Purpose
The purpose of this analysis was to collect and filter data for customers of Plan My Trip, a travel technology company in the hotel and lodging industry. A sample vacation travel itinerary for four cities in Mexico was generated, including a map with driving directions between the cities and a map with hotel and weather information for each city. Analysis was completed using pandas, gmaps, and requests Python libraries in a Jupyter Notebook. 

### Retrieving Weather Data
To begin, 2,000 random latitude and longitude coordinates were generated and combined. The coordinates were used to determine the corresponding city for eat latitude-longitude pair. For each unique city identified, a dataframe was created which includes city, country, latitude, longitude, maximum temperature, humidity, cloudiness, windspeed, and a description of the current weather for February 5, 2022. See the Weather Database folder for additional details including a table of the weather data in a csv file. 

### Creating a Customer Travel Destination Map
From these cities, the data was filtered to include only those with a maximum temperature between 75 and 90 degrees fahrenheit. These cities were displayed on a Google Map. See the Vacation Search folder for additional details, including an image of the Google Travel Destination Map.

![WeatherPy_Vacation_Map](https://user-images.githubusercontent.com/94587007/168627647-04335ef1-b6de-4d3d-a9c7-e995b3b16121.png)


### Creating a Travel Itinerary Map
A sample vacation travel itinerary for four cities in Mexico was generated, including a map with driving directions between the cities and a map with hotel and weather information for each city. See the Vacation Itineray folder for addition information. 

![WeatherPy_Travel_Map](https://user-images.githubusercontent.com/94587007/168627791-355fc367-2080-430d-8380-6a73dba7c6f9.png)

![WeatherPy_Travel_Map_Markers](https://user-images.githubusercontent.com/94587007/168627718-f8037113-989c-4db8-90b9-cc08b850a10c.png)
