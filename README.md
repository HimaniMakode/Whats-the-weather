# What's the Weather Like?
Background:

Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using CityPy, a simple Python library, and the OpenWeatherMap API.

The visualizations includce a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude Humidity (%) vs. Latitude Cloudiness (%) vs. Latitude Wind Speed (mph) vs. Latitude

The script accomplishes the following:

Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.

Performs a weather check on each of the cities using a series of successive API calls.

Includes a print log of each city as it's being processed with the city number and city name.

Saves both a CSV of all data retrieved and png images for each scatter plot.

Observable Trends:

1. Temperature increases towards the equator. However, temperature decreases after 20 degrees latitude.

![Latitude_vs_Temperature](https://user-images.githubusercontent.com/44784856/58780555-20950c80-858e-11e9-89e4-a9257eca5efe.png)

2. Cloudiness and humidity do not show a strong correlation to latitude.

![cvsh](https://user-images.githubusercontent.com/44784856/58780936-5090df80-858f-11e9-8dc5-62a7f0d22208.JPG)

3. Wind speed appears to slightly increase as we move away from the equator.

![Latitude_vs_Wind Speed](https://user-images.githubusercontent.com/44784856/58780963-61d9ec00-858f-11e9-9d09-3d3c162eec9a.png)
