# api_challenge
Latitude and Longitude Analysis 


Pick your ideal location spot around the world based on the weather of the day!

This python project brings together Citypy, the OpenWeatherMap API, and the Google Gmaps and Places API to give you a vacation destination list like no other!


Open up Weather.py for a loop that generates a list of 500 randomly generated cities around the world and their latitude and longitude coordinates. Using the OpenWeatherMap API, the code collects that day's humidity, wind speed, max temp, and more so you have perfect information about where you might want to go.

Weather.py gives extensive analysis comparing latitude to the windspeed, cloudiness, and the other weather metrics pulled from OpenWeather. 

Next go into Vacation.py to specify your ideal weather conditions. This code takes the 500+ cities run in Weather.py to narrow it to your ideal weather conditions. Want a dry mid-70s vacation spot? Or perhaps a tropical, humid paradise? This code will find you a dozen places to checkout. 

So you've planned your idea vacation spot! Now what? The final part of Vacation.py lets you find top hotels in every area you're interested in and plots them on a map with an info box so you can toggle back and forth to your hearts desire. 

Checkout 


Vacation planning made easy!

Citipy:
https://pypi.org/project/citipy/
Wing Chen (developer of citipy): https://pypi.org/user/wingchen/

OpenWeatherMap Documentation:
https://openweathermap.org/current

Gmaps Documentation:
https://developers.google.com/maps/documentation

Google Places Documentation:
https://developers.google.com/maps/documentation/places/web-service/overview