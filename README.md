# python-api-challenge

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Requirements
The requirements for "Part 1: WeatherPy" are the following

Create Plots to Showcase the Relationship Between Weather Variables and Latitude (30 points):

Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code (10 points)
Create a scatter plot to showcase the relationship between Latitude vs. Temperature (5 points)
Create a scatter plot to showcase the relationship between Latitude vs. Humidity (5 points)
Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness (5 points)
Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed (5 points)

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Compute Linear Regression for Each Relationship (40 points):

Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude (5 points)
Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude (5 points)
Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude (5 points)
Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude (5 points)
Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)
Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

The requirements for "Part 2: VacationPy" are the following (30 points):
Create a map that displays a point for every city in the city_data_df DataFrame (5 points)
Narrow down the city_data_df DataFrame to find your ideal weather condition (5 points)
For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates (10 points)
Add the hotel name and the country as additional information in the hover message for each city in the map. (10 points)
