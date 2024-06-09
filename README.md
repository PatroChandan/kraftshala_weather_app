# Weather App

if temperature less then 20 then it will show snowy image and if we selected darkmode then this background will show in the application.
![alt text](<src/assets/Dark snowy.png>)

if temperature grater then 20 then it will show sunny image and if we selected darkmode then this background will show in the application.
![alt text](<src/assets/Dark sunny.png>)

if temperature less then 20 then it will show snowy image and if we selected lightkmode then this background will show in the application.
![alt text](<src/assets/Light snowy.png>)

if temperature grater then 20 then it will show sunny image and if we selected lightkmode then this background will show in the application.
![alt text](<src/assets/Light sunny.png>)

## Live Demo

Check out the hosted link of the application : https://kraftshala-weather-app.vercel.app/

## Over View

This is a Weather Application this application provides users current weather information based on their input. This application built using HTML, CSS, and JavaScript, ReactJS and integrates with the Open Weather API to fetch real-time weather data.

## Features

- Current Weather: Display given inputs weather information, temperature.
- Location Search: Users can enter a city name to fetch weather information.
- Responsive Design: Works seamlessly on desktop, tablet, and mobile devices.
- Dark Mode: Toggle between dark and light themes for comfortable viewing in any environment.
- Detailed Weather Info: Additional weather details like humidity, wind speed, wind pressure and weather description.

## Usage

1. Enter a city name in the search bar and press Enter.
2. The app will display the current weather, temperature,feels like, humidity, max temperature, min-temrature, wind speed for the entered location.
3. Use the toggle switch to change between dark and light modes.

## Technologies Used

- React: For building the user interface.
- fetch: For making API requests.
- Open Weather API: For fetching weather data.

## Project Structure

- `src/components`: React components (SearchBar, WeatherCard, DarkModeToggle.js, Logo.js, Navbar.js).
- `src/index.css`: CSS module for styling components.
- `src/App.js`: Main application component.
