# API-Challenge
# Part 1 : Analysis of Weather Conditions at a given time vs. Latitude via Openweather API

This study began by generating a list of random lat/lng coordinates.
Utilizing the citipy python library, the nearest city to each coordinate was found.
API queries were run on each city, resulting in a data set of 594 locations
    
Date of the data was October 21,2020

Summary of Trends Observed:
1) On average, Temperature increases as locations near the equator.
2) Humidity and Cloudiness show little correlation with latitude.
3) This study is based on a single snapshot in time, local weather factors, as well as seasonality may also play a significant factor. (ie. late fall in Northern Hemishpere vs. Late Spring in Southern)

Figure 1- Scatter plot of temperature relationship to latitude:

![lat_vs_temp](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/lat_vs_temp.png)

Figure 2- Scatter plot of humidity vs. latitude

![hum](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/lat_vs_hum.png)

Figure 3- Scatter plot of cloudiness vs. latitude

![cld](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/lat_vs_cld.png)

Figure 4- Scatter plot of cloudiness vs. latitude

![wind](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/lat_vs_wind.png)

Figures 5,6:  Temperature vs. Latitude in each hemisphere
Both Hemispheres show a strong correlation to latitude (distance from equator)
For the Northern Hemisphere the r-value is -88
For the Southern Hemisphere the r-value is +.71 showing slightly higher variation


![north_temp](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/north_lat_temp.png)

![south_temp](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/south_lat_temp.png)

Figures 7,8:  Humidity vs. Latitude in each hemisphere

For the Northern Hemisphere the r-value is +.39 This appears to show a weak correlation of higher humidity with higher latitudes
For the Southern Hemisphere the r-value is -.06 showing little to no correlation


![north_hum](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/north_lat_hum.png)

![south_hum](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/south_lat_hum.png)

Figures 9,10:  Cloudiness vs. Latitude in each hemisphere

For the Northern Hemisphere the r-value is +.27 showing little to no correlation
For the Southern Hemisphere the r-value is -.13 showing little to no correlation


![north_cld](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/north_lat_cloud.png)

![south_cld](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/south_lat_cloud.png)

Figures 11,12:  Wind Speed vs. Latitude in each hemisphere

For the Northern Hemisphere the r-value is +.11 showing little to no correlation
For the Southern Hemisphere the r-value is -.15 showing little to no correlation


![north_hum](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/north_lat_wind.png)

![south_hum](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/south_lat_wind.png)


# Part 2 Plot Data via gmaps API



A Heatmap was created showing humidity of locations from part 1:

![hum_map](https://github.com/ajhibshman/API-Challenge/blob/main/VacationPy/images/humidity.png)

Data was filtered to include locations with 'Optimal' weather for a vacation, reducing the set to 22 locales.

Hotels nearest to the center of each city were then plotted against the map with marker labels.

![htl_map](https://github.com/ajhibshman/API-Challenge/blob/main/VacationPy/images/hotels2.PNG)






               



