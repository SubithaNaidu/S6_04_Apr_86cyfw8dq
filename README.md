
# 🌦️ WeatherWise - React Weather App

WeatherWise is a modern and responsive weather forecast application built with **React.js** and **Shadcn UI**, utilizing the **OpenWeather API**. It allows users to view current weather, hourly temperature charts, 5-day forecasts, search cities, toggle dark/light mode, and manage favorite locations.

## 🚀 Features

- 🌍 Detects user’s current location
- 🔎 Search for any city
- 🌡️ Displays current weather conditions
- 📈 Hourly temperature chart (Recharts)
- 📅 5-day weather forecast
- 💾 Search history
- ❤️ Favorite cities management
- 🌗 Dark / Light mode toggle
- 🌐 Fully responsive UI
- ☁️ Deployed on Hostinger

## 🛠️ Tech Stack

- **React.js** – Frontend framework
- **Shadcn UI** – UI components
- **React Router** – Routing
- **React Query (TanStack Query)** – API data fetching & caching
- **Axios** – HTTP client
- **Recharts** – Data visualization
- **OpenWeatherMap API** – Weather data
- **Hostinger** – Deployment

## 📂 Folder Structure

```
src/
├── components/
│   ├── Header.jsx
│   ├── WeatherDetails.jsx
│   └── ...
├── pages/
│   ├── Dashboard.jsx
│   └── CityPage.jsx
├── api/
│   └── weather.js
├── hooks/
│   └── useWeatherQuery.js
├── App.jsx
└── main.jsx
```

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/weatherwise-app.git
cd weatherwise-app
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root and add your OpenWeatherMap API key:

```
VITE_WEATHER_API_KEY=your_openweather_api_key
```

### 4. Run the Development Server

```bash
npm run dev
```

Open your browser at `http://localhost:5173` to see the app.

## 🧪 Deployment

1. Build the project:

```bash
npm run build
```

2. Upload `dist/` folder to Hostinger’s file manager or use FTP.
3. Configure domain and root directory as needed.

## 🙌 Acknowledgments

- [OpenWeatherMap API](https://openweathermap.org/api)
- [Shadcn UI](https://ui.shadcn.com)
- [React Query](https://tanstack.com/query)
- [Recharts](https://recharts.org/)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Made with ❤️ by Subitha
