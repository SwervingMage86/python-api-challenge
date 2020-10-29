# python-api-challenge

## Goal of This Code

The purpose of this program is to run a primary code, named WeatherPy, built find a list of cities across the goal and find current weather data on those cities.
The secondary code, named VacationPy, narrows down the list of cities found in WeatherPy to find the cities with the best weather on that day.

## How it Works

### WeatherPy

Pulls a randomly generates a list of latitude and longitude tuples and uses those values to create a list of cities using the CitiPy library.
Uses the generated list of cities to pull current weather data from the Open Weather Map API.
Pulls out cities with extreme humidity (greater than 95%)
Builds a series of scatterplots to view trends in weather data

### Vacation Py

Uses weather data generated in WeatherPy
Creates a heatmap using Google Maps API
Narrows down cities with 'perfect' weather for the day based on criteria
Finds closest hotel in that city
Plots those hotels on top of the heatmap