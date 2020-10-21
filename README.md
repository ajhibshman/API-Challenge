# API-Challenge
# Part 1 : Analysis of Weather Conditions at a given time vs. Latitude via Openweather API

This study began by generating a list of random lat/lng coordinates.
Utilizing the citipy python library, the nearest city to each coordinate was found.
API queries were run on each city, resulting in a data set of 594 locations
    Note- as lat/lng coordinates were randomly chosen and nearest city was found, an overrepresentation of cities near bodies of water exists
Date of the data was October 21,2020

Figure 1- Scatter plot of temperature relationship to latitude:

![lat_vs_temp](https://github.com/ajhibshman/API-Challenge/blob/main/WeatherPy/images/lat_vs_temp.png)

Figure 2- Scatter plot of humidity vs. latitude

![hum](https://github.com/ajhibshman/API-Challenge/blob/main/images/lat_vs_hum.png)

Figure 3- Scatter plot of cloudiness vs. latitude

![cld](https://github.com/ajhibshman/API-Challenge/blob/main/images/lat_vs_cld.png)

Figure 4- Scatter plot of cloudiness vs. latitude

![wind](https://github.com/ajhibshman/API-Challenge/blob/main/images/lat_vs_wind.png)

Figures 5,6:  Temperature vs. Latitude in each hemisphere
Both Hemispheres show a strong correlation to latitude (distance from equator)
For the Northern Hemisphere the r-value is -88
For the Southern Hemisphere the r-value is +.71 showing slightly higher variation


![north_temp](https://github.com/ajhibshman/API-Challenge/blob/main/images/north_lat_temp.png)

![south_temp](https://github.com/ajhibshman/API-Challenge/blob/main/images/south_lat_temp.png)

Figures 7,8:  Humidity vs. Latitude in each hemisphere

For the Northern Hemisphere the r-value is +.39 This appears to show a weak correlation of higher humidity with higher latitudes
For the Southern Hemisphere the r-value is -.06 showing little to no correlation


![north_hum](https://github.com/ajhibshman/API-Challenge/blob/main/images/north_lat_hum.png)

![south_hum](https://github.com/ajhibshman/API-Challenge/blob/main/images/south_lat_hum.png)

Figures 9,10:  Cloudiness vs. Latitude in each hemisphere

For the Northern Hemisphere the r-value is +.27 showing little to no correlation
For the Southern Hemisphere the r-value is -.13 showing little to no correlation


![north_hum](https://github.com/ajhibshman/API-Challenge/blob/main/images/north_lat_cloud.png)

![south_hum](https://github.com/ajhibshman/API-Challenge/blob/main/images/south_lat_cloud.png)

Figures 11,12:  Wind Speed vs. Latitude in each hemisphere

For the Northern Hemisphere the r-value is +.11 showing little to no correlation
For the Southern Hemisphere the r-value is -.15 showing little to no correlation


![north_hum](https://github.com/ajhibshman/API-Challenge/blob/main/images/north_lat_wind.png)

![south_hum](https://github.com/ajhibshman/API-Challenge/blob/main/images/south_lat_wind.png)






# Part 1 Conclusions
# Part 1 concerns
    - skew towards locations bordering large bodies of water rather than inland locations
    - snapshot of only one time period rather than a more broad sampling





