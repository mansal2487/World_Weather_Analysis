# World_Weather_Analysis

## Process
For the main part of this assignment, I started by generating a list of 2,000 lists, each containing a random latitude and longitude. I then used the citipy module to get the nearest city to each of these coordinates. Using an API call to OpenWeatherMap, I gathered weather information about each of these cities then compiled everything I've gathered into a dataframe. Then, I filtered this dataframe based on the users temperature preference, found the name of the nearest hotel using Google API, and added each name to the dataframe. Finally, I plotted the points on a map using Google API and added a pop-up marker to each of these locations that contained the hotel name and current weather information.

## Usefulness
The last, small part of this assignment included picking four cities that are relatively close to each other then plotting a walking path that connects each of the cities. This assignment was very helpful for me as one of my coworkers uses Google API to geocode and reverse geocode data that I QA/QC and this gave me some insight into how I can help to verify other parts of his work! It also gave the idea of using Google API to create a list of directions and a map that shows a running route that starts and ends at my house and is X miles long.
