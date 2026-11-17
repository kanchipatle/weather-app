# Weather App – Nagpur

A simple browser-based weather interface that requests current weather information for Nagpur from the OpenWeatherMap API.

## Features
- Requests current weather data
- Displays temperature in Celsius
- Displays weather description, humidity, and wind speed
- Displays a weather icon
- Shows loading and error messages

## Technologies
- HTML5
- CSS3
- JavaScript
- OpenWeatherMap API

## Run locally
1. Create an API key in your own OpenWeatherMap account.
2. Configure the key locally in the application before running it.
3. Open `index.html` in a browser.

## Security note
Never commit API keys or other secrets to a public repository. The current source file contains a hardcoded API key; revoke or rotate that exposed key in your OpenWeatherMap account, then update the app to use a replacement without committing it. Removing a key from the latest file does not remove it from earlier Git history.

## Possible next improvements
- Move JavaScript into a separate file.
- Add city search and input validation.
- Avoid inserting untrusted API response text with `innerHTML`.
- Use a small backend proxy if the API key must remain private.
