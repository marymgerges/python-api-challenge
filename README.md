# python-api-challenge
Part 1: WeatherPy
I initialized with dependencies and setup, then imported the OpenWeatherMap API key and imported citipy to determine the cities based on latitude and longitude.
Next, I generated the cities list by using the citipy library.
Then I created plots to showcase the relationship between weather variables (temperaute, humidity, cloudiness, wind speed) and latitude.
For the second requirement, I computed linear regression for each relationship and plotted scatter plots with the regression lines.

Part 2: VacationPy
I initialized with dependencies and setup, then imported the Geoapify API key and loaded the csv file created in part 1 into a Pandas DataFrame.
 I created a map that displays a point for every city in the  DataFrame where the size of the point should be the humidity in each city.
Next, I narrowed down the DataFrame to find the ideal weather condition.
I then Create a new DataFrame to store the city, country, coordinates, and humidity and added an empty column, "Hotel Name," to the DataFrame so I can store the hotel found using the Geoapify API.
Then, for each city, I used the Geoapify API to find the first hotel located within 10,000 metres of your coordinates and printed these results.
Lastly, I added the hotel name and the country as additional information in the hover message for each city and displayed it in the map.
