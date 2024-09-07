# Weather Dashboard

This is a simple Weather Dashboard application that allows users to search for a city's weather information and view the current weather and a 5-day forecast.

## Features

- Search for a city to get the current weather information
- View temperature, humidity, wind speed, and UV index for the selected city
- View a 5-day weather forecast
- Save search history and click on past searches to quickly view weather information again
- Clear search history

## Technologies Used

- HTML
- CSS (Custom CSS, no Bootstrap)
- JavaScript
- Axios for API requests
- OpenWeatherMap API

## How to Use

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/your-repository.git
    ```
2. Navigate to the project directory:
    ```sh
    cd your-repository
    ```
3. Open `index.html` in your preferred web browser.

## API Key

This project uses the OpenWeatherMap API. To use this project, you will need an API key from OpenWeatherMap.

1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Obtain your API key from the [API keys section](https://home.openweathermap.org/api_keys).
3. Replace the placeholder API key in the `script.js` file with your own API key:
    ```javascript
    const APIKey = "your_api_key_here";
    ```

## Project Structure

|-- index.html |-- css | |-- style.css |-- js | |-- script.js

## License

This project is licensed under the MIT License.
