# World Weather Summary
The purpose of this analysis was to provide a way for customers to find potential travel destinations based on temperature requirements.  

The code was set to generate 2,000 random latitude and longitude combinations.  From this data, nearest cities were provided by the citypy module and populated into a dataframe with their weather data using the OpenWeatherMap API. 

The next step was to allow users to filter these locations by specifying a temperature range.  The user could then view their filtered option on a map and click the location markers to select destinations.

The final step was to add these selected destinations into an itinerary for the user.
