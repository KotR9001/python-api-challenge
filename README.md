# python-api-challenge
Weather and Vacation Analysis


Undertook an assignment to determine the effect of latitude & longitude on weather and to use that analysis to filter data from a
dataframe to help plan a vacation.<br />
<br />
<br />
First, an API call was made to the OpenWeatherMap API to obtain a random list of 500+ world cities with their coordinates and current
weather information.<br />
Next, used Pandas to put this data in a dataframe.<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/5c38669e-32c4-480c-928d-52697b2ec99d)<br />
After that, exported the data to a CSV and an HTML file.<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/ef32b135-08b4-4f99-ab31-7f8bc51dfc69)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/3f2395bc-3281-4193-88d7-cc62fc43d454)<br />
<br />
<br />
Then used the data to create scatter plots to visualize the following relationships:<br />
-Temperature (F) vs. Latitude<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/c463845d-17bf-41af-b1ca-a75293f268fa)<br />
-Humidity (%) vs. Latitude<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/5a0c295d-0e76-4cb1-98db-e44c23a60110)<br />
-Cloudiness (%) vs. Latitude<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/c6a8c3e2-9b13-4fd5-b486-3d3b8cdcd215)<br />
-Wind Speed (mph) vs. Latitude<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/94196f53-8add-49b6-b9da-c7429fc08992)<br />
<br />
Next, created separate dataframes for Northern & Southern Hemisphere data.<br />
Used the data from these to recreate the above relationships, but with linear regression applied.<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/40aa7b0e-817d-4d95-bcf1-dd83bf51502a)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/9bd87941-4199-4eba-9436-f4684a75e47a)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/e040a020-0d28-42df-a537-16c024ffa28f)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/ae0c941a-e015-4c10-ab10-1e05ece11c4e)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/6977c337-2247-443c-a26b-f23c754a2fa6)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/a0541f94-a30a-4b51-acc3-8b8ba63c6a96)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/75094532-e04a-496c-9493-539a06f27a56)<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/8d9ba097-0b42-4575-aaf0-d8c411028a2a)<br />
<br />
<br />
Made the following conclusions.<br />

-------------------------------------------------------------------------------------------------------------------
1. The latitude is only a good predictor of temperature. It is not a good predictor of humidity, cloudiness, or wind speed.
-------------------------------------------------------------------------------------------------------------------
2. The wind speeds seem to pick up at the very highest latitude values in the Northern Hemisphere, suggesting that perhaps arctic winds contribute to the wind speed.
-------------------------------------------------------------------------------------------------------------------
3. There are fewer data points, with data not collected as far south in the Southern Hemisphere as it is far north in the Northern Hemisphere. As such, the conclusions for the Southern Hemisphere are not as strong as the conclusions for the Northern Hemisphere.
<br />
<br />
After the weather analysis was completed, started the vacation analysis.<br />
<br />
First, created a Humidity Heatmap with GMaps.<br />
Then, applied a weather filter to create a dataframe of ideal cities.<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/082c8403-f6c0-40bb-b07e-ed628d961350)
<br />
<br />
Next, found the closest hotel for each city in this dataframe.<br />
![image](https://github.com/KotR9001/python-api-challenge/assets/57807780/1f7b499e-e70e-43ee-835e-cd6358e558cf)
<br />
<br />
