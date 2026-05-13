# React Weather App

A simple weather application built with React and Vite that lets users search for a city and view live weather information.

## Features

- Search weather by city name
- View temperature in Celsius
- See humidity, minimum temperature, maximum temperature, and feels-like temperature
- Weather-based icons and visuals
- Clean UI built with Material UI

## Tech Stack

- React
- Vite
- Material UI
- OpenWeather API

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/dhwanithummar23/react-weather-app.git
cd react-weather-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create environment variables

Create a `.env` file in the project root and add:

```env
VITE_API_URL=https://api.openweathermap.org/data/2.5/weather
VITE_API_KEY=your_api_key_here
```

### 4. Start the development server

```bash
npm run dev
```

Open the local URL shown in the terminal to use the app in your browser.

## Available Scripts

```bash
npm run dev
```

Runs the app in development mode.

```bash
npm run build
```

Builds the app for production.

```bash
npm run preview
```

Previews the production build locally.

```bash
npm run lint
```

Runs ESLint checks on the project.

## Project Structure

```text
src/
  App.jsx
  WeatherApp.jsx
  SearchBox.jsx
  InfoBox.jsx
```
