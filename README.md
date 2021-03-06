# API-challenge

This repository contains an analysis of weather data for over 500 cities randomly selected using the full range of latitudes and longitudes. The analysis aims to investigate whether latitude influences certain weather metrics.

## WeatherPy

The WeatherPy analysis (housed in the WeatherPy Jupyter notebook file) looks for potential correlations as well as linear relationships between latitude and the weather variables temperature (Fahrenheit), percent humidity, percent cloudiness, and wind speed (mph). The following trends were observed:

1. The only weather metric which appears to be influenced by latitude (all else held constant) is temperature.
2. Both temperature and humidity appear to have potential parabola-shaped correlations with latitude. Non-linear regression techniques may be a better fit and reveal more about the nature of these relationships.
3. Both cloudiness and wind speed appear to have no significant relationship with latitude.

The Output Data folder contains:
* Two CSV files containing the weather data for all cities (one containing unit conversions for temperature and wind speed)
* Four correlation plots
* Eight linear regression plots (northern and southern hemisphere were isolated for each of the four weather metric regressions)
