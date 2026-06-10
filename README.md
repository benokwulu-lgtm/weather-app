# WeatherNow 🌤️

A clean, responsive weather app that fetches live weather data for any city in the world using the OpenWeatherMap API.

Built with vanilla HTML, CSS, and JavaScript — no frameworks, no libraries.

---

## Features

- Live weather data for any city worldwide
- Displays temperature, weather condition, feels like, humidity, wind speed, and visibility
- Clean dark UI with smooth hover and focus states
- Responsive layout — works on mobile and desktop
- Error handling for invalid cities and network failures
- Enter key support for faster searching

---

## Screenshots

![WeatherNow App](screenshot.png)

---

## Tech Stack

| Layer      | Technology                          |
|------------|--------------------------------------|
| Markup     | HTML5                                |
| Styling    | CSS3 (Custom Properties, Flexbox, Grid) |
| Logic      | Vanilla JavaScript (ES6+, Async/Await) |
| Data       | OpenWeatherMap Current Weather API   |

---

## Project Structure

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2. Get a free API key

- Sign up at [openweathermap.org](https://openweathermap.org)
- Go to **API Keys** in your dashboard
- Copy your key

### 3. Add your API key

Open `app.js` and replace the placeholder on line 1:

```javascript
const API_KEY = "your_api_key_here";
```

### 4. Open the app

Open `index.html` directly in your browser. No build step or server required.

---

## API Reference

This project uses the [OpenWeatherMap Current Weather API](https://openweathermap.org/current).

**Endpoint:**

**Key response fields used:**

| Field | Description |
|---|---|
| `name` | City name |
| `sys.country` | Country code |
| `main.temp` | Temperature in °C |
| `main.feels_like` | Feels like temperature |
| `main.humidity` | Humidity percentage |
| `weather[0].description` | Weather condition text |
| `weather[0].icon` | Icon code for weather image |
| `wind.speed` | Wind speed in m/s |
| `visibility` | Visibility in metres |

---

## Important Note

Never commit your real API key to a public repository. For production projects, store keys in environment variables using a `.env` file and add it to `.gitignore`.

This project is for learning purposes — the key is hardcoded for simplicity.

---

## Author

Built by [Your Name](https://github.com/your-username)

