# World_Weather_Analysis

# Overview of Project

The purpose of this challenge was to improve our PlanMyTrip app so that it contains weather descriptions along with our weather data. Customers will be able to use input statements to filter the data for their weather preferences, which will be used to identify  travel destinations and nearby hotels. Finally, I will have created both a travel itinerary and travel map as well as a marker layer map.

- Retrieve Weather Data
- Create a Customer Travel Destination Map
- Create a Travel Itinerary Map

# Resources

- The data source used in this project was retrieved from Open Weather website, Google gmaps and the statistical analysis was performed with Citipy Library.
- Python 3.7.6, Pandas Library, Matplotlib, Jupyter Notebook, APIs and JSON Traversals.

# Results

### Retrieve Weather Data
- The Weather Data was retrieved based on a set of 2,100 random latitudes and longitudes. Using the Open Weather map and retrieving the information with API, the cities weather data was collected with the current weather description and saved in a new DataFrame.

![Weather_database](https://github.com/acegal1/World_Weather_Analysis/blob/main/Weather_Database/Weather_database.jpg)


### Create a Customer Travel Destination Map
- Using customer weather preferences, potential travel destinations were identified along with nearby hotels. The destinations are identified with a marker layer map with pop-up markers.

![WeatherPy_vacation_map](https://github.com/acegal1/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.jpg)

### Create a Travel Itinerary Map
- Using Google Directions API a travel route was created to display positional coordinate between four cities chosen by the customer.

![WeatherPy_travel_map](https://github.com/acegal1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.jpg)

- A marker layer map with pop-up was added to provide customized information to the user describing the name of the city, country, hotel and current weather description.

![WeatherPy_travel_markers](https://github.com/acegal1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_markers.jpg)


