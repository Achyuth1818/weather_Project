#Weather detection Projection
This weather project is a web application that lets users check the current weather for any city. Here's a straightforward breakdown of how it works:

User Input:

The user types a city name into a search box and clicks a search button.
Fetching Weather Data:

The app uses the OpenWeatherMap API to get the weather data for the entered city. It sends a request to the API with the city name and a special key (API key) to access the data.
Handling the Response:

If the city is found, the app receives the weather data and displays it on the webpage:

The city's name
The temperature in Celsius
The wind speed in kilometers per hour
The humidity percentage
A weather icon that shows if it's cloudy, clear, rainy, drizzling, or misty
If the city is not found, an error message is displayed instead.

Displaying the Data:

The app updates the webpage to show the weather information and the appropriate weather icon based on the current conditions.
Event Listener:

The search button has an event listener that triggers the weather data fetching process when clicked.
This project provides a quick and easy way for users to see the current weather in any city they choose.
