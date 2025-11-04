# Weather App
A simple weather application built with **HTML**, **CSS**, and **JavaScript**. It lets users search for any city and view the current weather details using data from the **OpenWeatherMap API**.

## Features

* Search for weather by city name
* Shows the country's flag based on the city location
* Displays temperature in Celsius
* Includes weather description, cloud percentage, humidity, and pressure
* Clean, minimal, and responsive design
* Subtle error animation for invalid city names

## Technologies Used

* **HTML5** for structure
* **CSS3** for layout and styling
* **JavaScript (ES6)** for functionality and API integration
* **OpenWeatherMap API** for live weather data
* **FlagsAPI** for displaying country flags

## How to Use

1. Download or clone this repository to your computer.
2. Open the folder and find the `index.html` file.
3. Open `index.html` in your web browser.
4. Type a city name in the search box and press Enter.
5. The app will display:

   * City name and flag
   * Current temperature
   * Weather condition
   * Cloud, humidity, and pressure details

## Setting Up the API

This app uses the **OpenWeatherMap API**, and you’ll need your own API key.

1. Go to [OpenWeatherMap](https://openweathermap.org/api) and sign up for a free account.
2. Generate an API key.
3. Open `script.js` and replace the example key with your own:

   js
   let id = 'YOUR_API_KEY_HERE';

## Example Output

When you search for a city, you’ll see information similar to this:

City: London  
Temperature: 12°C  
Description: Overcast Clouds  
Clouds: 98% | Humidity: 56% | Pressure: 1001 hPa

## Error Handling

If the city name is not found or entered incorrectly, the app will briefly shake to indicate an error.

## File Structure
weather-app/
│
├── index.html
├── style.css
└── script.js

## Credits

* Weather data: [OpenWeatherMap](https://openweathermap.org/)
* Flags: [FlagsAPI](https://flagsapi.com/)
* Icons: [Font Awesome](https://fontawesome.com/)



