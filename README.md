# World_Weather_Analysis
## Overview of the analysis: 

this project is focus on how to Collect and analyze weather data across cities worldwide. The PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data. In this analysis we write a Python’s script using Panda’s libraries, Jupyter Notebook, and Matplotlib. The analysis of the data will be split into three main parts, or stages.
  1. Collect the Data
    o	Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
    o	Use the citipy module to list the nearest city to the latitudes and longitudes.
    o	Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
    o	Parse the JSON data from the API request.
2. Collect the following data from the JSON file and add it to a DataFrame:
    	City, country, and date
    	Latitude and longitude
    	Maximum temperature
    	Humidity
    	Cloudiness
    	Wind speed
3. Exploratory Analysis with Visualization
    o	Create scatter plots of the weather data for the following comparisons:
      	Latitude versus temperature
      	Latitude versus humidity
      	Latitude versus cloudiness
      	Latitude versus wind speed
    o	Determine the correlations for the following weather data:
      	Latitude and temperature
      	Latitude and humidity
      	Latitude and cloudiness
      	Latitude and wind speed
    o	Create a series of heatmaps using the Google Maps and Places API that showcases the following:
      	Latitude and temperature
      	Latitude and humidity
      	Latitude and cloudiness
      	Latitude and wind speed
4. Visualize Travel Data
Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:
  1. Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
  2. Create a heatmap for the new DataFrame.
  3. Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
  4. Store the name of the first hotel in the DataFrame.
  5. Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
## Results: 
The following image show that rural cities had the highest average fare per driver ($55.49) and ride ($34.62), while urban cities had the lowest average fare per driver ($16.57) and ride ($24.53).
 
The following multiple line graph show the trend analysis of fare by city type, per week. Urban cities had the highest total fare in general compare with rural and suburban cities. Rural cities had the lowest total fare per week while suburban cities based in the medial between urban and rural cites. 
 
There is an increasing in the total fare in the last week of February in all city types. 
## Summary: 
The analysis and visualizations provide in this project will help PyBer to improve access to ride-sharing services and determine affordability for underserved neighborhoods.  Based on the results, there are three business recommendations to the CEO for addressing any disparities among the city types.
-	Analysis on the size of the population and the population component by age and employment in each city, will clarify the differences between cities.
-	Providing an analysis of the average daily working time (morning, day, and evening) which will also show further differences in cities.
-	A descriptive analysis of the distance for each trip may give another dimension to the analysis and further explain the differences between cities.
