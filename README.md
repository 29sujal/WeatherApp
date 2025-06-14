# 🌤️ Weather App

A clean, responsive **Weather Application** built with **HTML, CSS, and JavaScript**, using the [OpenWeatherMap API](https://openweathermap.org/api) to fetch real-time weather data for any city worldwide.

---

## 🚀 Features

* 🌍 Search for any city globally
* 🌡️ Real-time temperature in Celsius
* 💧 Displays humidity and wind speed
* ⛅ Dynamic weather icons (sun, clouds, rain, etc.)
* 🛑 Handles errors gracefully (e.g., invalid city name)
* 📱 Mobile-responsive card layout

---

## 📸 Preview

> *You can add a screenshot here later for visual appeal.*

```html
<!-- Replace with your actual screenshot -->
![Weather App Screenshot](images/screenshot.png)
```

---

## 🛠️ Tech Stack

* **HTML5** – page structure
* **CSS3** – styling and responsive layout
* **JavaScript (Vanilla)** – logic, API integration
* **OpenWeatherMap API** – weather data source

---

## 🔧 Getting Started

### 1. Clone the repo:

```bash
git clone https://github.com/29sujal/WeatherApp.git
cd WeatherApp
```

### 2. Open `index.html` in your browser

You can double-click it or open it through VS Code Live Server.

---

## ⚙️ Replace API Key

The script uses the OpenWeatherMap API. You need to:

1. Sign up at [openweathermap.org](https://openweathermap.org/) and get your free API key.
2. In the `script.js` file, replace:

```js
const apiKey = "YOUR_API_KEY";
```

with:

```js
const apiKey = "your-real-api-key";
```

---

## 📁 Project Structure

```
WeatherApp/
├── index.html         # Main HTML file
├── style.css          # App styling
├── script.js          # API and weather logic
└── images/            # Weather icons
    ├── clear.png
    ├── clouds.png
    ├── drizzle.png
    ├── humidity.png
    ├── mist.png
    ├── rain.png
    ├── snow.png
    └── wind.png

