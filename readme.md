# Weather App

A simple weather application that allows users to check the current weather conditions for a specific location.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [API Key](#api-key)
- [License](#license)

## Demo

https://iankushsingh.github.io/weather-web2.0/

![Weather App Screenshot](img/screenshot.png)

## Features

- Display current weather conditions (temperature, description, etc.).
- Search for weather by location.
- Responsive design for various devices.

## Technologies Used

- HTML
- CSS
- JavaScript
- https://www.weatherapi.com/docs/

## Getting Started

To get a copy of this project up and running on your local machine, follow these steps:

1. Clone the repository:

    ```bash
    https://github.com/iankushsingh/Weather-web2.0.git
    ```

2. Open the project folder:

    ```bash
    cd weather-web2.0
    ```

## How to Use

1. Open the `index.html` file in a web browser.
2. Enter the desired location in the search bar.
3. Click the "Search" button to retrieve and display the weather information.

## API Key

This project uses a weather API to fetch real-time weather data. To use the API, you need to obtain an API key by signing up on the API provider's website.

Once you have the API key, create a file named `config.js` in the root directory and add the following code:

```javascript
// config.js
const apiKey = 'cefcd70f32405f5998871bb3dff62dba';

export default apiKey;
