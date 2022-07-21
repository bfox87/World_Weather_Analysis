# PlanMyTrip App: Further Development

## Overview:
PlanMyTrip likes the app that has been built thus far and want additional features built for the beta testers. The wish list includes an input feature where users can input their temperature preferences to then identify potential cities to travel to and nearby hotels in those cities. This way users can then pick a few cities to create their itineary and a travel route between the chosen destinations.

## Process:
Current weather data was pulled in for cities using the OpenWeatherMap API and re-organzied into a dataframe. Then this city list was narrowed based on user input regarding their temperature preferences. After that, Google's Map API was used to create a marker map of these narrowed cities and nearby hotels in these cities. Finally, Google's Directions API was used to create trip itineary directions between a few destinations chosen by the user.
