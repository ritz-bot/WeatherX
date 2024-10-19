
# Live Weather App - WeatherX🌦️

Welcome to the **Live Weather App** project! This application is built using **React.js** and provides real-time weather updates for any location in the world. The app fetches weather data from an external API and displays it dynamically, along with visual cues that adapt to the current weather conditions.

## Project Overview

In this project, you'll learn how to use React.js to create a dynamic and interactive weather application. The app demonstrates key concepts such as API integration, error handling, state management, and responsive design.

The core features of the application include:
- Real-time weather updates for any location worldwide 🌍
- Dynamic background changes based on weather conditions 🎨
- Error handling for invalid locations 🛑
- Current temperature, humidity, wind speed, and dynamic date display 📅
- Weather type-based icons (clear, clouds, rain, snow, haze, mist) 🌤️
- Fully responsive design for different screen sizes and devices 📱💻
  
![Xnip2024-10-19_16-29-18](https://github.com/user-attachments/assets/470d0784-864a-42f1-a963-b9492b33404b)

## Features

1. **Search for Any Location**:
   - Users can search for any city in the world using the search input field.
   - For example, you can search for cities like London, Tokyo, New York, Paris, etc.
   - If an invalid location is entered, an error message ("Location Not Found") is displayed.
     
   ![Xnip2024-10-19_16-29-45](https://github.com/user-attachments/assets/6f9bc53d-0720-42e3-bfb1-5e2715f05d08)

2. **Dynamic Weather Data**:

   - The app displays weather information including:
     - Location name
     - Temperature in Celsius 🌡️
     - Weather conditions (clear, clouds, rain, snow, haze, mist) ☁️🌧️❄️
     - Humidity 💧
     - Wind speed 🌬️
     - Current date, which is dynamically updated and not hardcoded 📅

3. **Dynamic Backgrounds**:
   - The background of the application changes dynamically depending on the current weather conditions.
   - Each weather condition (clear, clouds, rain, etc.) has its own unique background and icon.

4. **Responsive Design**:
   - The application is fully responsive, ensuring a seamless experience on both mobile and desktop devices.
   - The layout adapts to various screen sizes for optimal usability.

## Technologies Used

- **React.js**: The core framework for building the user interface.
- **OpenWeather API**: To fetch real-time weather data based on the user's location.
- **CSS3**: For styling the app and implementing the responsive design.
- **JavaScript (ES6+)**: For managing app logic and handling API requests.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/live-weather-app.git
   ```
2. Navigate into the project directory:
   ```bash
   cd live-weather-app
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Create an `.env` file in the root directory and add your OpenWeather API key:
   ```env
   REACT_APP_API_KEY=your_openweather_api_key
   ```
5. Start the development server:
   ```bash
   npm start
   ```

The app should now be running at `https://weatherx.ridhampuri.in/`.

## How It Works

- **Fetching Weather Data**: The app fetches data from the OpenWeather API using the city name input by the user.
- **Displaying Data**: Once the weather data is retrieved, it is displayed on the card, showing the location, weather condition, temperature, wind speed, humidity, and current date.
- **Error Handling**: If the user inputs an invalid location, an error message is shown, and no weather data is displayed.
- **Responsive Design**: The app adapts to different screen sizes, providing a consistent experience across mobile and desktop devices.

## Future Enhancements

- Add support for more detailed weather forecasts (e.g., hourly forecasts, extended weekly forecasts).
- Implement location services to automatically detect and display weather information for the user's current location.
- Add unit conversion options (e.g., switch between Celsius and Fahrenheit).

## Contributing

Feel free to open issues or submit pull requests if you'd like to contribute to the project.
=======
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
>>>>>>> 67a65e8 (first Push)
