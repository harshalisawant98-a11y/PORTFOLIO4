# PORTFOLIO4
OpenWeatherMap
# Weather API Integration Demo

This project demonstrates how to connect to the OpenWeatherMap API using JavaScript's `fetch()` method.

## Setup
1. Copy the `index.html` file.
2. Replace the API key with your own if needed.
3. Open the file in a browser.

## Output
- Console: Full JSON response from the API.
- Webpage: Displays temperature and weather condition for the chosen city.

## Requirements
- Modern browser (Chrome, Edge, Firefox).
- Valid API key from [OpenWeatherMap](https://openweathermap.org/api).

## Example
-Mumbai
-Temperature: 32°C
-Condition: scattered clouds

---

## Endpoint Documentation

### Endpoint Used
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric (api.openweathermap.org in Bing)

- **q** → City name (e.g., `Mumbai`)
- **appid** → Your API key
- **units** → `metric` for Celsius, `imperial` for Fahrenheit

### Response Format (JSON)
```json
{
  "weather": [
    { "description": "scattered clouds" }
  ],
  "main": {
    "temp": 32.0,
    "humidity": 70
  },
  "name": "Mumbai"
}
