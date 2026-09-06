# 🌤️ SkyCast — Modern Weather App

A beautiful, responsive and modern weather application built with **HTML, CSS and JavaScript**.

SkyCast provides real-time weather information, city search, geolocation support and a 7-day forecast — all wrapped inside a premium **glassmorphism UI**.

---

## ✨ Features

* 🌡️ Real-time temperature
* 🤒 Feels-like temperature
* 🌤️ Dynamic weather conditions
* 🔎 Search weather by city
* 📍 Detect weather using your current location
* 💧 Humidity percentage
* 💨 Wind speed
* 🧭 Atmospheric pressure
* 👁️ Visibility
* 🌅 Sunrise time
* 🌇 Sunset time
* 📅 7-day weather forecast
* 💧 Daily precipitation probability
* 📱 Fully responsive design
* 🪟 Modern glassmorphism interface
* ✨ Animated background effects
* ⚡ No API key required

---

## 🛠️ Tech Stack

| Technology              | Usage                               |
| ----------------------- | ----------------------------------- |
| HTML5                   | Application structure               |
| CSS3                    | UI, animations & responsive design  |
| JavaScript              | API integration & application logic |
| Open-Meteo API          | Weather & geocoding data            |
| Browser Geolocation API | Current location detection          |

---

## 📂 Project Structure

```text
skycast/
│
├── index.html
└── README.md
```

The application is intentionally kept lightweight and can run from a single HTML file.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/skycast.git
```

### 2. Open the project

```bash
cd skycast
```

### 3. Run the application

You can simply open:

```text
index.html
```

For the best experience, use a local development server such as **VS Code Live Server**.

---

## 🌐 API

SkyCast uses **Open-Meteo** for weather and geocoding data.

No API key is required.

### Weather API

The application retrieves:

* Current temperature
* Relative humidity
* Apparent temperature
* Weather condition
* Wind speed
* Surface pressure
* Visibility
* Daily maximum/minimum temperatures
* Precipitation probability
* Sunrise
* Sunset

### Geocoding API

The city search uses Open-Meteo's geocoding service to convert a city name into latitude and longitude coordinates.

---

## 📍 Location Detection

SkyCast supports browser-based geolocation.

When the user clicks:

```text
📍 My Location
```

the browser requests permission to access the user's approximate location.

If permission is granted, SkyCast fetches weather data for that location.

If permission is denied, users can still search for any city manually.

---

## 🎨 UI Design

SkyCast uses a modern visual style based on:

* Glassmorphism
* Gradient backgrounds
* Soft shadows
* Blur effects
* Animated ambient lighting
* Rounded cards
* Responsive layouts
* Minimal typography

The interface is designed to look great on both desktop and mobile devices.

---

## 📱 Responsive Design

The application adapts automatically to different screen sizes.

### Desktop

```text
┌──────────────────────────────────────────────┐
│ SkyCast                         My Location  │
├──────────────────────────────────────────────┤
│ Search City                       Search     │
├───────────────────────┬──────────────────────┤
│                       │                      │
│    Current Weather    │    Highlights       │
│                       │                      │
├───────────────────────┴──────────────────────┤
│              7-Day Forecast                  │
└──────────────────────────────────────────────┘
```

### Mobile

```text
┌──────────────────────┐
│ ☀️ SkyCast            │
├──────────────────────┤
│ Search city...       │
│       Search         │
├──────────────────────┤
│ Current Weather      │
│                      │
│       28°            │
│      ☀️              │
├──────────────────────┤
│ Today's Highlights   │
│                      │
│ Humidity │ Wind      │
│ Pressure │ Visibility│
├──────────────────────┤
│ 7-Day Forecast       │
└──────────────────────┘
```

---

## ⚙️ How It Works

### City Search

```text
User enters city
       ↓
Geocoding API
       ↓
Latitude + Longitude
       ↓
Weather API
       ↓
Weather data
       ↓
UI update
```

### Current Location

```text
User clicks "My Location"
          ↓
Browser Geolocation API
          ↓
Latitude + Longitude
          ↓
Weather API
          ↓
Weather information
```

---

## 🔐 Privacy

SkyCast does not require an account or API key.

Location access is only requested when the user explicitly chooses the **My Location** feature.

The application does not need to store the user's location.

---

## 🧪 Browser Compatibility

SkyCast works with modern browsers that support:

* Fetch API
* ES6 JavaScript
* CSS Backdrop Filter
* Geolocation API

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

---

## 🐛 Troubleshooting

### Weather isn't loading

Check your internet connection and reload the page.

### City isn't found

Try using a larger or more recognizable city name, for example:

```text
Delhi
Mumbai
London
New York
Tokyo
Paris
```

### Location doesn't work

Make sure:

1. Your browser supports geolocation.
2. Location permission is enabled.
3. The application is running in a secure context or localhost.

---

## 🔮 Future Improvements

Possible future upgrades:

* 🌙 Dark/Light theme switcher
* ⏰ Hourly weather forecast
* 📊 Temperature charts
* ⭐ Favorite cities
* 🌍 Automatic country detection
* 🔔 Weather alerts
* 🌧️ Animated rain/snow effects
* 🗺️ Weather map
* 📈 Historical weather
* 🌡️ Celsius/Fahrenheit toggle
* 📲 Progressive Web App (PWA)
* 📴 Offline support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/amazing-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git commit -m "Add amazing feature"
```

5. Push the branch.

```bash
git push origin feature/amazing-feature
```

6. Open a Pull Request.

---

## 📄 License

This project is available for personal and educational use.

You are free to modify the code and use it as a starting point for your own projects.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

Made with ❤️ using **HTML, CSS & JavaScript**.

### 🌤️ SkyCast

**Beautiful weather, simplified.**
