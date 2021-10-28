# World_Weather_Analysis
Module 6

# World Weather and Travel Destinations Analysis 

## Overview
The scope of the project was to add a weather description to the weather data that was previously provided.  Upon the preferred weather temperature parameters input by the user, potential travel destinations and nearby hotels will be output.  For this test, four cities were provided along with the travel itinerary for this trip.

## Results
The initial analysis provided roughly 737 randomized latitudes and longitudes. The associated maximum temperature, humidity, cloudiness, windiness and country were provided and was exported into a CSV file.

To further narrow in on the travel itinery provided, the inputs of a minimum and maximum temperature were provided of 75 and 90, respectively. Any empty rows were removed from the data and loding was searched for within 5000 meters and was exported into a CSV file.

In the final analysis, markers were displayed for these coordinates.

Four cities were selected and the travel itinerary was provided for a trip to Brazil. The travel mode selected was for driving. The hotels are marked on the map as well for ease of travelling.

## Summary

I encountered numerous issues in connecting to the API. My data continued to not be read in full by the API despite being able to successfully call the .head() and .tail(). I continued to receive ConnectonError and ConnectionResetErrors which contributed to a higher usage of API calls as I was troubleshooting the issue.  No real solution was provided aside from one of the TA's walking me through how to except the specific error so the code could continue running. I thought the code was failing, in general, and not that one line was potentially causing an issue so the TA experience and knowledge was more than appreciated.