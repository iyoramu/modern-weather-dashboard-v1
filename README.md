# 🌦️ Modern Weather Dashboard

A sleek, animated weather dashboard with dynamic backgrounds and real-time data visualization. Built with pure HTML, CSS, and JavaScript.

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Now-green?style=for-the-badge)](https://iyoramu.github.io/modern-weather-dashboard-v1/)

![Weather Dashboard Screenshot](https://via.placeholder.com/800x500/4361ee/ffffff?text=Weather+Dashboard+Screenshot)

## ✨ Features

- **Dynamic Weather Animations** (rain, snow, sunshine, clouds)
- **Responsive Design** that works on all devices
- **Beautiful UI** with glassmorphism effects
- **Mock Data System** that simulates seasonal weather patterns
- **Location Detection** (with graceful fallback)
- **Real-time Updates** with refresh capability

## 🛠️ Technology Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=flat&logo=font-awesome&logoColor=white)
![Geolocation API](https://img.shields.io/badge/Geolocation_API-4285F4?style=flat&logo=google-maps&logoColor=white)

## 🚀 Quick Start

### Clone the Repository

```bash
git clone https://github.com/iyoramu/modern-weather-dashboard-v1.git
cd modern-weather-dashboard-v1
```

### Usage

1. **For Local Development**:
   - Simply open `index.html` in your browser
   - No build step required (pure HTML/CSS/JS)

2. **For Production**:
   - Deploy the entire folder to any static hosting (GitHub Pages, Netlify, Vercel, etc.)

3. **Using the App**:
   - Allow location access when prompted for real weather data
   - If location is blocked, enjoy simulated weather data
   - Click the refresh button (↻) to update weather

## 🌈 Weather Conditions Supported

- Sunny ☀️
- Rainy 🌧️  
- Cloudy ☁️
- Snowy ❄️
- Night 🌙
- Thunderstorms ⚡
- Mist 🌫️

## 🔧 Connect to Real Weather API (Optional)

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Replace the mock data function in the script with:

```javascript
async function getRealWeatherData(lat, lon) {
    const API_KEY = 'your_api_key_here';
    const response = await fetch(
        `https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${API_KEY}&units=metric`
    );
    return await response.json();
}
```

## 📜 License

MIT License

Copyright (c) 2023 [IRUTABYOSE Yoramu]

---

Made with ❤️ by [IRUTABYOSE Yoramu]  
[![GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?style=flat&logo=github)](https://github.com/iyoramu/modern-weather-dashboard-v1)