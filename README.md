# Weather App

This is a simple weather application that allows users to search for the weather in various cities. It uses the OpenWeatherMap API to fetch weather data and display it to the user.

## Features

- Search for current weather by city name
- Display temperature, humidity, and wind speed
- Show appropriate weather icon based on weather conditions
- Handle invalid city names with an error message

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Getting Started

### Prerequisites

- A modern web browser
- Internet connection

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. Open `index.html` in your preferred web browser.

### Usage

1. Enter the name of a city in the search box.
2. Click the search button.
3. View the weather information for the city.

## API Key

This application requires an API key from OpenWeatherMap. You can get a free API key by signing up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

Replace the `apikey` variable in the `index.html` file with your own API key:

```javascript
const apikey = "your_api_key_here";
