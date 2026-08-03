# Weather App

A modern weather application that fetches and displays current weather data based on user location or city search.

## Features

- **Search by City**: Enter any city name to get current weather conditions
- **Geolocation Support**: Use your current location to get weather data
- **Modern UI**: Beautiful glass-morphism design with smooth animations
- **Comprehensive Data**: Displays temperature, feels like, humidity, wind speed, and pressure
- **Responsive Design**: Works on desktop and mobile devices

## Setup Instructions

### 1. Get an OpenWeatherMap API Key

The app uses the OpenWeatherMap API to fetch weather data. You need a free API key:

1. Go to [OpenWeatherMap](https://openweathermap.org/)
2. Sign up for a free account
3. Navigate to the API keys section in your account
4. Copy your API key (it will look like: `a1b2c3d4e5f6g7h8i9j0`)

### 2. Add Your API Key

Open `index.html` and replace the placeholder API key on line 68:

```javascript
const API_KEY = 'YOUR_API_KEY'; // Replace with your OpenWeatherMap API key
```

Replace `YOUR_API_KEY` with your actual API key.

### 3. Run the Application

Simply open `index.html` in your web browser. No build process or server required!

## Usage

### Search by City
1. Enter a city name in the search box
2. Click the search button or press Enter
3. View the current weather conditions

### Use Current Location
1. Click the "Use My Location" button
2. Allow location access when prompted
3. View the weather for your current location

## Weather Data Displayed

- **Temperature**: Current temperature in Celsius
- **Feels Like**: Perceived temperature
- **Humidity**: Relative humidity percentage
- **Wind Speed**: Wind speed in meters per second
- **Pressure**: Atmospheric pressure in hPa
- **Weather Icon**: Visual representation of current conditions
- **Description**: Text description of weather conditions

## Technologies Used

- **HTML5**: Structure
- **TailwindCSS**: Styling (via CDN)
- **Font Awesome**: Icons (via CDN)
- **Vanilla JavaScript**: Functionality
- **OpenWeatherMap API**: Weather data

## API Rate Limits

The free OpenWeatherMap tier allows:
- 60 calls/minute
- 1,000,000 calls/month

This is more than sufficient for personal use.

## Troubleshooting

**"City not found" error**: Check the city name spelling and try again.

**"Failed to fetch weather data"**: Ensure you have a valid API key and internet connection.

**Location not working**: Make sure location services are enabled in your browser settings.

## License

This project is open source and available for educational purposes.
