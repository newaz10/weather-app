# Weather App

This project is a weather application built with React that allows users to effortlessly check the current weather conditions for cities around the globe. By leveraging real-time data from the OpenWeatherMap API, it provides essential information such as temperature, humidity, wind speed, and overall weather status, ensuring a smooth and dynamic experience for users.

## Features

- **Real-Time Weather Data:** Fetches data such as temperature, humidity, wind speed, and weather conditions using OpenWeatherMap API.
- **Dynamic Weather Search:** Users can search for any city's weather conditions.
- **Loading Animations:** Smooth spinner animations during data fetches.
- **Icon-Based Weather Display:** Displays icons based on the current weather conditions.
- **Responsive UI:** Ensures a seamless user experience on devices of all sizes.

## Tech Stack

- **React** (with hooks for state management and lifecycle methods)
- **OpenWeatherMap API**

## Setup and Installation

### Prerequisites

- Node.js (>=14.x)
- npm or yarn

### Steps

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd weather-app
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Create a .env file in the root directory and add your OpenWeatherMap API key:**
   ```bash
   VITE_APP_ID=your_openweathermap_api_key
   ```
4. **Start the development server:**
   ```bash
   npm run dev
   ```
5. **Open the app in your browser at [http://localhost:5173](http://localhost:5173)**

## File Structure

```plaintext
weather-app/
├── public/                  # Static assets
├── src/                     # Source files
│   ├── assets/              # Icons
│   ├── components/          # React components
│   ├── App.jsx              # Root component
│   ├── index.css            # Global CSS file
│   ├── main.jsx             # Entry point
└── .env                     # Environment variables
```

## Components

### Weather.jsx

The main component that handles:

- Fetching weather data using the OpenWeatherMap API.
- Managing application state (loading, error, and weather data).
- Displaying weather information dynamically.

### Weather.css

Styles for the weather application, including:

- Animations
- Responsive design

## Conclusion

If you encounter any issues or have suggestions for improvement, feel free to open an issue or create a pull request.
