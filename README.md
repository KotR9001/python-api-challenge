# python-api-challenge
Weather and Vacation Analysis


An assignment was undertaken to determine the effect of latitude & longitude on weather and to use that analysis to filter data from a
dataframe to help plan a vacation.


First, an API call was made to the OpenWeatherMap API to obtain a random list of 500+ world cities with their coordinates and current
weather information.

Next, Pandas was used to put this data in a dataframe.

After that, the data was exported to a CSV and an HTML file.


The data was then used to create scatter plots to visualize the following relationships:

-Temperature (F) vs. Latitude

-Humidity (%) vs. Latitude

-Cloudiness (%) vs. Latitude

-Wind Speed (mph) vs. Latitude


The next step involved creating separate dataframes for Northern & Southern Hemisphere data.

The data from these were used to recreate the above relationships, but with linear regression applied.


The following conclusions were made.

-------------------------------------------------------------------------------------------------------------------
1. The latitude is only a good predictor of temperature. It is not a good predictor of humidity, cloudiness, or wind speed.
-------------------------------------------------------------------------------------------------------------------
2. The wind speeds seem to pick up at the very highest latitude values in the Northern Hemisphere, suggesting that perhaps arctic winds contribute to the wind speed.
-------------------------------------------------------------------------------------------------------------------
3. There are fewer data points, with data not collected as far south in the Southern Hemisphere as it is far north in the Northern Hemisphere. As such, the conclusions for the Southern Hemisphere are not as strong as the conclusions for the Northern Hemisphere.



After the weather analysis was completed, the vacation analysis was started.

First, a Humidity Heatmap was created with GMaps.

Then, a weather filter was applied to create a dataframe of ideal cities.

Next, the closest hotel was found for each city in this dataframe. 
