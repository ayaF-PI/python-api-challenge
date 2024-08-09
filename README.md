# python-api-challenge



## Overview

This project is focuses on analyzing weather data using Python, APIs, and JSON traversal. The project is divided into two main parts:

1. **WeatherPy**: Visualizing weather data across various cities to explore the relationship between weather variables and latitude.
2. **VacationPy**: Utilizing weather data to identify ideal vacation spots and display these locations on a map.

## Part 1: WeatherPy

### Objective

To analyze weather patterns by visualizing the relationship between various weather parameters (like temperature, humidity, cloudiness, and wind speed) and latitude.

### Steps

1. **Data Collection**: 
   - Use the OpenWeatherMap API to gather weather data for over 500 cities worldwide.

2. **Data Visualization**: 
   - Generate scatter plots to show the relationships between latitude and each weather variable, including:
     - Latitude vs. Temperature
     - Latitude vs. Humidity
     - Latitude vs. Cloudiness
     - Latitude vs. Wind Speed

3. **Linear Regression**: 
   - Perform linear regression on each variable for both hemispheres to observe trends and correlations.

### Outputs

- Scatter plots with regression lines illustrating the relationship between latitude and various weather parameters.

## Part 2: VacationPy

### Objective

To identify cities with ideal weather conditions for a vacation and display them on a map, along with nearby hotels.

### Steps

1. **Filter Cities**: 
   - Narrow down the cities based on preferred weather conditions (e.g., temperature, wind speed, cloudiness).

2. **Find Hotels**: 
   - Use the Geoapify API to find the nearest hotel within 10,000 meters of each city’s coordinates.

3. **Map Visualization**: 
   - Plot the selected cities on a map, with hotel information available on hover.

### Outputs

- A map with points representing cities that match the ideal weather conditions, including hotel information.

## Conclusion

This project helps to understand how weather variables change with latitude and how to utilize API data for practical applications like vacation planning.