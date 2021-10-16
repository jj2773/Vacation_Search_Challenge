# Vacation_Search_Challenge
Module 6 Challenge using Python and APIs to search for vacation spots by allowing users to input temperature ranges.  Once the temperature ranges are selected a map is generated where four cities can be selected to travel between.  A directions map with weather information is made from the four cities selected.

##  Approach
## Weather Database
Random GPS coordinates are generated and citipy returns a nearest city.  This city is then passed to the OpenWeather API which returns weather conditions.

## Vacation Search
By limiting cities according to the users desirable temperature ranges, a subset for vacation planning is offered.

## Vacation Itinerary
After allowing the user to select a start, stop, and three waypoints, gmaps is leveraged with Google's API to generate directions maps.