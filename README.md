# World_Weather_Analysis
Click here to view the analysis files: [WeatherPy.ipynb](https://github.com/caitlinbighem/World_Weather_Analysis) | [VacationPy.ipynb](https://github.com/caitlinbighem/World_Weather_Analysis/blob/main/VacationPy.ipynb)

## Purpose
The purpose of this assignment is to create a map that allows users planning a vacation to search potential destinations by specific weather preferences. While incorporating Google API's, the user is also provided with a list of recommended hotels that fits within the search parameters of ideal travel locations.

## Overview
After producing a list of 2,000 random latitudes and longitudes, these were used to create the above-mentioned vacation map. Also using the randomly generated coordinates, we recovered and assembled a list of nearby cities by using the citipy module. Utilizing the OpenWeatherMap API, we requested the most current and up to date weather data from each individual city the user included in the search parameters. The subsequent map we see as an end result offers the users descriptions of each destination on our generated list such as hotel, city, country and current weather conditions. 