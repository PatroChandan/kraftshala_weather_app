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

1.Enter a city name in the search bar and press Enter.
2.The app will display the current weather, temperature,feels like, humidity, max temperature, min-temrature, wind speed for the entered location.
3.Use the toggle switch to change between dark and light modes.

## Technologies Used

- React: For building the user interface.
- fetch: For making API requests.
- Open Weather API: For fetching weather data.

## Project Structure

- `src/components`: React components (SearchBar, WeatherCard, DarkModeToggle.js, Logo.js, Navbar.js).
- `src/index.css`: CSS module for styling components.
- `src/App.js`: Main application component.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
