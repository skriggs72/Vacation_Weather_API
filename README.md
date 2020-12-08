# python-api-challenge

I created a Python script to visualize teh weather of 500+ cities across the globe of varying distances from the equator.

Part I = WeatherPy

To create the Python script I used citipy and OpenWeatherMap API.

My first objective is to build a series of scatter plots to showcase the following relationships:

    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude
    
My second objective is to run linear regression on each relationship, only this time separatiniig them into Norhtern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

    Northern/Southern Hemisphere - Temperature (F) vs. Latitude
    NOrthern/Southern Hemisphere - Humidity (%) vs. Latitude
    Northern/Southern Hemisphere - Cloudiness (%) vs. Latitude
    Northern/Southern Hemisphere - Wind Speed (mph) vs. Latitude
    
Part II - VacationPy

Now I want to use my skills in working with weather data to plan future vacations. I used jupyter-gmaps and the Google Places API

    Create a heat map that displays the humidity for every city from part I of the project.
    Narrow down the DataFrame to find my ideal weather condition. For example:
        
        A max temperature lower than 80 degrees but higher than 70.
        Wind speed less than 10 mph.
        Zero cloudiness
        Drop any rows that don't contain all three conditions.
        
    To run the code:
        
        Install citypy in your python environment
        Save OpenWeatherMap API Key as 'weather_api_key'
        Google API Key as 'g_key'
        Create API Keys and store in in the 'api_keys.py' file before running the Jupyter notebooks.
    