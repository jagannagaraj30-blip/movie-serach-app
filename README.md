# Weather Dashboard

An innovative weather dashboard built with React and Vite, featuring real-time weather data, 5-day forecasts, interactive charts, and a sleek dark/light mode toggle.

## Features

- 🌤️ Real-time current weather display
- 📅 5-day weather forecast
- 📊 Interactive temperature trend charts
- 🌙 Dark/Light mode toggle
- 🔍 Search for any city worldwide
- 🎨 Smooth animations with Framer Motion
- 📱 Responsive design
- ⚡ Fast loading with Vite

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)

4. Replace `YOUR_OPENWEATHERMAP_API_KEY` in `src/App.jsx` with your actual API key

5. Start the development server:
   ```bash
   npm run dev
   ```

6. Open [http://localhost:5173](http://localhost:5173) in your browser

## Technologies Used

- React 18
- Vite
- Axios for API calls
- Chart.js for data visualization
- Framer Motion for animations
- Lucide React for icons
- OpenWeatherMap API

## API Key Setup

This app uses the OpenWeatherMap API. To get your free API key:

1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Generate an API key in your dashboard
4. Replace the placeholder in `src/App.jsx`

Note: The free tier allows 1000 calls per day, which is sufficient for personal use.

## Build for Production

```bash
npm run build
```

## License

MIT
