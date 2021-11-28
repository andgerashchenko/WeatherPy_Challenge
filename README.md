# World_Weather_Analysis

The purpose of this analysis is to use API calls to gather the current weather for a random set of latitudes and longitudes. Once that analysis is generated, Google maps will be utilized to map driving directions of a possible vacation by choosing 4 different cities within the USA.

## Results
After generating the random latitudes and longitudes, the results were entered into a dataframe so they could be analyzed further.
Once the dataframe was compiled, the Google API was able to be utilized. At first markers that included the weather data in that specific city were added to the map. This would give the user an idea of the area that they would like to travel to. This information is very useful to help the user decide what type of vacation they are looking for.
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/79814533/143785896-786706c2-d913-4d79-b662-a642a314e599.png)
The above shows a few examples of what information is included.

Once the country and cities of the desination are chosen, the search was narrowed down to only include the chosen cities.
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/79814533/143785909-d6c85c38-e93b-4b18-b1c5-1106478804ec.png)

The final step is to create a driving directions map to show the route that the user would have to take in order to visit all of the chosen cites and then return to their start point. Using the same cities as in the screen shot above, the driving directions were generated and mapped for the user.
![WeatherPy_travel_map](https://user-images.githubusercontent.com/79814533/143785915-1a032466-48cc-40e9-b968-3c5438baf979.png)
