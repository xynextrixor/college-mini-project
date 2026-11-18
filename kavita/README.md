# Kavita Weather Dashboard

A simple real-time weather and location dashboard built with HTML, CSS, and JavaScript. It does not require a framework or a build process.

## Features

- Search by city
- Show current temperature and weather conditions
- Show humidity, wind speed, pressure, visibility, and feels-like temperature
- Switch between Celsius and Fahrenheit
- View a five-day forecast
- Use browser location
- Search and select locations on an OpenStreetMap map
- Load weather for a clicked or dragged map location

## Open the project in VS Code

1. Install [Visual Studio Code](https://code.visualstudio.com/) if it is not already installed.
2. Open VS Code.
3. Select **File > Open Folder** and open the `college-mini-project` folder.
4. Open `kavita/weather-dashboard.html`.
5. Install the **Live Server** extension in VS Code.
6. Right-click inside `weather-dashboard.html` and select **Open with Live Server**.

You can also open the HTML file directly in a browser, but Live Server is recommended for browser location access and map features.

## Copy the project code

To run this project in a new VS Code folder:

1. Create a folder named `kavita`.
2. Create a file named `weather-dashboard.html` inside it.
3. Copy the complete code from `kavita/weather-dashboard.html` in this repository.
4. Paste the code into the new file.
5. Save the file.
6. Open the folder in VS Code and run it with Live Server.

## Get an OpenWeather API key

1. Open https://home.openweathermap.org/users/sign_up.
2. Create a free OpenWeather account.
3. Sign in and open https://home.openweathermap.org/api_keys.
4. Copy the API key shown on that page.
5. Open `weather-dashboard.html` in VS Code.
6. Find this line:

```javascript
const OPENWEATHER_API_KEY = "YOUR_OPENWEATHER_API_KEY";
```

7. Replace only `YOUR_OPENWEATHER_API_KEY` with the key copied from OpenWeather.

```javascript
const OPENWEATHER_API_KEY = "your_real_api_key";
```

Do not share or publish your real API key. GitHub and other services may block a public secret. It can take some time for a new OpenWeather key to become active.

## Which APIs are used

This project uses the free OpenWeather APIs:

- **Geocoding API** - finds a city or address and provides its coordinates
- **Current Weather API** - provides current weather details
- **5 Day / 3 Hour Forecast API** - provides the forecast

It also uses:

- **OpenStreetMap** - map tiles
- **Nominatim** - map search and reverse location details
- **Leaflet** - map display and marker dragging

The project does not use One Call 3.0, so it does not require the One Call subscription.

## API key setup error

If the project says to add the API key:

- Replace `YOUR_OPENWEATHER_API_KEY`
- Save the HTML file
- Refresh Live Server
- Wait for the new key to activate if it was created recently

If OpenWeather returns `401 Unauthorized`, check that the key is correct and that a paid One Call key is not being required. The free APIs used here require a normal activated OpenWeather API key.

## Using the dashboard

1. Enter a city in the search box, for example `Hapur, IN`.
2. Select **Search**.
3. Use the **°C / °F** button to change temperature units.
4. Select **Use my location** to use browser location access.
5. Select a forecast card to view that day's details.
6. Search or click on the map to select another location.
7. Drag the map marker to change coordinates.
8. Select **Load weather here** to fetch weather for the selected map location.
