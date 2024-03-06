Module 6 Challenge

#"What is the weather like as we approach the equator?"

PART 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude. Next, you'll create a series of scatter plots to showcase the following relationships:
*Latitude vs. Temperature
*Latitude vs. Humidity
*Latitude vs. Cloudiness
*Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship. Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values and create the following plots:
*Northern Hemisphere: Temperature vs. Latitude
*Southern Hemisphere: Temperature vs. Latitude
*Northern Hemisphere: Humidity vs. Latitude
*Southern Hemisphere: Humidity vs. Latitude
*Northern Hemisphere: Cloudiness vs. Latitude
*Southern Hemisphere: Cloudiness vs. Latitude
*Northern Hemisphere: Wind Speed vs. Latitude
*Southern Hemisphere: Wind Speed vs. Latitude

Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:
*Create a map that displays a point for every city in the city_data_df DataFrame
*Narrow down the city_data_df DataFrame to find your ideal weather condition
*Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity
*For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates
*Add the hotel name and the country as additional information in the hover message for each city on the map