Skyline — Weather App
A weather app that works for any city, in any country, with a 7-day forecast. No API key, no sign-up, no billing — it uses [Open-Meteo](https://open-meteo.com/), a free public weather API.
What it does

Search any city worldwide (with autocomplete suggestions as you type)
"Use my location" button to get weather where you are
Current conditions: temperature, feels-like, humidity, wind, precipitation
Hourly forecast strip for the next 24 hours
7-day forecast
°C / °F toggle (wind and precipitation units switch along with it: km/h + mm for Celsius, mph + inches for Fahrenheit)
Background and icons shift based on the current condition (clear/cloudy/rain/snow/storm/fog, and day vs. night)
Remembers your last few searched cities (via localStorage) as quick-access chips
Spinner + status text while a request is in flight
Project structure

weather-app/
├── index.html      → page structure
├── style.css       → all styling
├── app.js          → search, API calls, rendering logic
Credits

Weather & geocoding data: [Open-Meteo](https://open-meteo.com/)
Reverse geocoding for "Use my location": [BigDataCloud](https://www.bigdatacloud.com/) write code for git hub for README.md
