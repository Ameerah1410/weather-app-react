Weather App

The Weather App is a simple web application that allows users to check the current weather and forecast for a specified location and the user's own location. It provides detailed information such as temperature, humidity, wind speed, and more, using data from the OpenWeatherMap API. The app was built using React and styled using Tailwind CSS.

Features

- Current weather details including temperature, feels-like temperature, and weather conditions.
- Time and location information.
- Hourly and daily weather forecasts.
- Responsive design for a seamless user experience on various devices.
  
Technologies Used

- React.js: A JavaScript library for building user interfaces.
- OpenWeatherMap API: Provides weather data for the app.
- Luxon: A library for handling dates and times in JavaScript.
- React Toastify: Used for displaying toast messages.

Getting Started

Prerequisites

Ensure that Node.js and npm are installed on your machine.

Installation

1. Clone the repository:
   
  git clone https://github.com/your-username/your-weather-app.git

2. Navigate to the project directory:

  cd your-weather-app

3. Install dependencies:

  npm install

4. Usage
   
Get an API key from OpenWeatherMap and replace the placeholder in src/services/weatherServices.js with your API key.

5.Start the development server:

  npm start

6. Open your browser and go to http://localhost:3000 to view the app.

Configuration

Update the default location and units in src/App.js by modifying the query and units state.


Acknowledgments
Thanks to OpenWeatherMap for providing the weather data.
