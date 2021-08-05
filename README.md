# python-api-challenge

The WeatherPy Jupyter notebook will select a random set of values for latitude and longitude and use citipy will be used to identify the nearest city to each set.  Unique city names will be stored in a list.

Weather conditions for each unique city will be retrieved using openweathermap.com API calls in sets of 50 and stored in a dataframe.  Cities not found and those with humidity over 100% will be removed from the dataframe.  The data will be exported as a csv file.

A function will be used to plot the city latitude vs various weather conditions and save each image as a png file.

The VacationPy Jupyter notebook will import the weather data exported from the WeatherPy notebook.  Using gmaps, a heatmap of the humidity for each city will be created.

Various criteria will be used to filter the list of cities down to those with ideal vacation weather.

Using google APIs, the nearest hotel to each city's latitude and longitude coordinates will be found and stored in a dataframe.  Each hotel will be plotted on the humidity heatmap with info boxes displaying the hotel name, city and country.