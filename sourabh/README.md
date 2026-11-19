# Sourabh Live Weather

## Project overview
A live weather search using the OpenWeather Current Weather API.

## Run in VS Code
1. Open `sourabh/weather-card.html`.
2. Use Live Server.
3. Create or copy an OpenWeather API key.
4. Enter the key and city name.
5. Select **Get live weather**.

## Get an OpenWeather API key
1. Sign up at https://openweathermap.org.
2. Open https://home.openweathermap.org/api_keys.
3. Copy an active API key.
4. Enter it into the project.

The project saves the key in browser `localStorage`, not in source code.

## How it works
- The city input supplies the search location.
- `fetch()` sends a request to OpenWeather.
- The JSON response is converted to JavaScript data.
- Temperature, country, and weather description are displayed.
- HTTP or API errors are shown in the message area.

Example endpoint:
`https://api.openweathermap.org/data/2.5/weather?q=Hapur&appid=KEY&units=metric`

## Viva questions

**Q1. What is an API?**
An API allows one software system to request data or services from another system.

**Q2. What is JSON?**
JSON is a lightweight text format for structured data.

**Q3. Why use `fetch()`?**
It sends HTTP requests from JavaScript.

**Q4. What is `async/await`?**
It handles asynchronous operations more clearly.

**Q5. What is an API key?**
It is a credential that identifies an application or account.

**Q6. How is a key kept private?**
Do not commit it to GitHub. Use an environment variable or backend in a real production project.
