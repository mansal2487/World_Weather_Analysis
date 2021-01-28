# World_Weather_Analysis

## Process
For the main part of this assignment, I started by generating a list of random latitudes and longitudes. I then used the citipy module to get the nearest city to each of these coordinates. Using an API call to OpenWeatherMap, I gathered weather information about each of these cities then added all of the information to a dataframe. Then I filtered this dataframe based on the users temperaure preference and added the nearest hotel to each of the records. Finally, I added a pop-up marker to each of these locations that contained the hotel name and current weather information.

## Usefulness
This assignment was very helpful for me as one of my coworkers uses Google Maps API to geocode and reverse geocode data that I QA/QC and this gave me some insight into how I can help to verify other parts of his work! It also gave the idea of using Google Maps API to create a list of directions and a map that shows a running route that starts and ends at my house and is X miles long.
