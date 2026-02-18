# Weather Dashboard

A responsive and interactive Weather Dashboard built using HTML, CSS, JavaScript, and D3.js.  
This project fetches real-time and 5-day forecast weather data from the OpenWeatherMap API and visualizes it using dynamic charts and summary cards.

---

## Overview

The Weather Dashboard allows users to select a city and view:

- Current temperature
- Humidity levels
- Rainfall data
- Wind speed
- Air Quality Index (AQI)
- 5-day forecast visualizations

The application uses D3.js to render interactive charts and provides a modern, responsive UI layout.

---

## Features

- Real-time weather data integration
- 5-day forecast visualization
- Temperature line chart
- Temperature bar chart
- Humidity area chart
- Rainfall bar chart
- Wind speed line chart
- AQI monitoring and status display
- Dynamic summary cards
- Responsive design
- City selection dropdown

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- D3.js
- OpenWeatherMap API

---

## API Integration

This project uses the OpenWeatherMap API to fetch:

- Current weather data
- 5-day forecast data
- Air Pollution (AQI) data

You must generate your own API key from:

https://openweathermap.org/api

Replace the API key in the script section:

```javascript
const API_KEY = "YOUR_API_KEY_HERE";
