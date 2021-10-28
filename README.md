# World_Weather_Analysis
Module 6

# World Weather and Travel Destinations Analysis 

## Overview
The scope of the project was to add a weather description to the weather data that was previously provided.  Upon the preferred weather temperature parameters input by the user, potential travel destinations and nearby hotels will be output.  For this test, four cities were provided along with the travel itinerary for this trip.

## Results
The initial analysis provided roughly 737 randomized latitudes and longitudes. The associated maximum temperature, humidity, cloudiness, windiness and country were provided and was exported into a CSV file.

To further narrow in on the travel itinery provided, the inputs of a minimum and maximum temperature were provided of 75 and 90, respectively. Any empty rows were removed from the data and lodging was searched for within 5000 meters and was exported into a CSV file.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/90632470/139317886-5a859c7f-fa39-4a09-b633-4db6e8b735b3.PNG)

In the final analysis, markers were displayed for these coordinates.

Four cities were selected and the travel itinerary was provided for a trip to Brazil. The travel mode selected was for driving. The hotels are marked on the map as well for ease of travelling.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/90632470/139317822-370a0e7c-8da8-46bc-855e-620ee7b37afb.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/90632470/139317808-aab282a2-a09a-484a-8954-f7d1343ca8a2.png)

## Summary

I encountered numerous issues in connecting to the API. My data continued to not be read in full by the API despite being able to successfully call the .head() and .tail(). I continued to receive ConnectonError and ConnectionResetErrors which contributed to a higher usage of API calls as I was troubleshooting the issue.  No real solution was provided aside from one of the TA's walking me through how to except the specific error so the code could continue running. I thought the code was failing, in general, and not that one line was potentially causing an issue so the TA experience and knowledge was more than appreciated.
