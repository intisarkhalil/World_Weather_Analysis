# World_Weather_Analysis
## Overview of the analysis: 

### Purpose: 
Collecting and analyzing weather data across cities worldwide. Using PlanMyTrip to recommend ideal hotels based on clients' weather preferences. This can be done through various steps:
1. Generate a set of 2,000 random latitudes and longitudes.
2. Retrieve the nearest city, and perform an API call with the OpenWeatherMap. 
3. In addition to the city weather data, we use your API to retrieve the current weather description for each city. 
4. Create a new DataFrame containing the updated weather data. 
5. Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those           destinations on a marker layer map with pop-up markers. Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the       customer’s possible travel destinations. 
6. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

### Method: 
Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data. In this analysis we write a Python’s script using Panda’s libraries, Jupyter Notebook, and Matplotlib. The analysis of the data will be split into three main parts, or stages.
  1. Collect the Data
  ```
    o	Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
    o	Use the citipy module to list the nearest city to the latitudes and longitudes.
    o	Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
    o	Parse the JSON data from the API request.
  ```
2. Collect the following data from the JSON file and add it to a DataFrame:
```
    	City, country, and date
    	Latitude and longitude
    	Maximum temperature
    	Humidity
    	Cloudiness
    	Wind speed
 ```
3. Exploratory Analysis with Visualization
    o	Create scatter plots of the weather data for the following comparisons:
    ```
      	Latitude versus temperature
      	Latitude versus humidity
      	Latitude versus cloudiness
      	Latitude versus wind speed
    ```
    o	Determine the correlations for the following weather data:
    ```
      	Latitude and temperature
      	Latitude and humidity
      	Latitude and cloudiness
      	Latitude and wind speed
   ```
    o	Create a series of heatmaps using the Google Maps and Places API that showcases the following:
   ```
      	Latitude and temperature
      	Latitude and humidity
      	Latitude and cloudiness
      	Latitude and wind speed
    ```
4. Visualize Travel Data
Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

   - Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
   - Create a heatmap for the new DataFrame.
   - Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
   - Store the name of the first hotel in the DataFrame.
   - Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
5. Find the Relationship Between Variables Using Linear Regression. 
 - create scatter plots for each weather parameter on the Northern and Southern Hemispheres. 
 - add a regression line equation and correlation coefficient to each scatter plot.
7. Use GoogleMap and API places to create Heatmaps and identify customer Vacation.

## Results: 
   1. Generate a set of 2,000 random latitudes and longitudes.

   ![retrieve](https://user-images.githubusercontent.com/62036983/138986355-9390dda4-e0a8-43c4-b3bb-b94bbd14375c.png)

   2. In addition to the city weather data, we use your API to retrieve the current weather description for each city. 

   ![weather](https://user-images.githubusercontent.com/62036983/138986570-884b8026-c60b-4f6f-a8a3-06f25c4ead1c.png)

   3. Retrieve the  hotels data , and perform an API call with the OpenWeatherMap. 

   ![hotel ](https://user-images.githubusercontent.com/62036983/138986520-50e847e8-b086-4120-9889-9d3d6993eb98.png)

   4. Create a new DataFrame containing a selected four cities the updated weather data. 

   ![combine](https://user-images.githubusercontent.com/62036983/138986630-6828805a-40d4-4800-ad77-666eb606b54b.png)

   5. Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those           destinations on a marker layer map with pop-up markers. Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the       customer’s possible travel destinations. 

   ![WeatherPy_travel_map](https://user-images.githubusercontent.com/62036983/138985138-e7640706-3ccc-4594-a989-588a27ac0aa7.png)

   6. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

   ![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/62036983/138985106-57d63041-886c-45be-8009-59a14e9ccc4f.png)



