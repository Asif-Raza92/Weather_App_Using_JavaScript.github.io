# Weather_App_Using_JavaScript.github.io
Thanks For Support
Weather App 🌦️
A simple and interactive weather application that allows users to search for current weather conditions of any city around the world. The app fetches real-time weather data using the OpenWeatherMap API and displays key details like temperature, humidity, wind speed, and a weather icon representing the current condition.

Disclaimer : This project is made with the help of Tutorial and I add some features and changed its User interface also take help of Ai to solve only error in projects.

Features
🌍 Search by City: Enter any city name to get its current weather details.
📉 Error Handling: Displays "Invalid City Name" when a non-existent city is entered.
🌡️ Weather Details: Shows temperature, humidity, and wind speed in an easy-to-read layout.
🖼️ Dynamic Icons: Weather icons change dynamically based on the current weather condition (e.g., sunny, cloudy, rainy).
🎨 Modern UI: A sleek, gradient-based design for an engaging user experience.
Technologies Used
HTML: Structure of the app.
CSS: Styling for the weather card and overall design.
JavaScript: Logic for fetching and displaying weather data.
OpenWeatherMap API: Fetches real-time weather data.
Installation and Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/weather-app.git
cd weather-app
Add your API key:

Go to OpenWeatherMap and sign up for an API key.
Replace the placeholder apiKey in the script section of index.html with your API key:
javascript
Copy code
const apiKey = "YOUR_API_KEY";
Run the app:

Open the index.html file in any web browser.
Usage
Search for Weather:

Enter the name of the city in the search box and press the search button (🔍) or hit Enter.
If the city exists, the weather details will be displayed.
Error Handling:

If you type an invalid or non-existent city name, you’ll see an error message: "Invalid City Name".
File Structure
php
Copy code
weather-app/
├── index.html         # Main HTML file
├── style.css          # Styling for the app
├── images/            # Folder containing weather icons
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── rain.png
│   ├── default.png
├── README.md          # Project documentation (this file)
Screenshots
Weather Display

Error Message

Future Improvements
Add a feature to detect the user's location and show local weather.
Provide a 7-day forecast for searched cities.
Make the app responsive for mobile devices.
Add animations for weather changes.
