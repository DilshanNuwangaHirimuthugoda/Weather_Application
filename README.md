# Weather Application

A simple and interactive weather application that lets users check the weather based on their location. Built using HTML, CSS, and JavaScript, this app fetches weather data from the OpenWeather API and displays it with a clean and responsive design.

## Folder Structure
weather-app/

├── images/ # Weather icons (clear, rain, snow, etc.)

├── styles.css # CSS for styling the app

├── index.html # The main HTML file

└── index.js # JavaScript file to fetch weather data and handle logic

## Table of Contents
1.  [Features](#features)
2.  [Demo](#demo)
3.  [Technologies Used](#technologies-used)
4.  [Installation](#installation)
5.  [Usage](#usage)
6.  [API Key](#api-key)
7.  [Folder Structure](#folder-structure)
8.  [License](#license)

## Features
*   Search for weather by city name.
*   Displays the current temperature, weather description, humidity, and wind speed.
*   Different weather icons based on the weather condition (Clear, Rain, Snow, Clouds, Haze).
*   Error message for invalid locations.
*   Mobile-friendly design.
*   Option to use current location for weather details.

## Demo
You can view the live demo of the app [here]( https://dilshannuwangahirimuthugoda.github.io/Weather_Application/   ) 

## Technologies Used
*   HTML – Structure of the webpage[1][3].
*   CSS – Styling and layout of the app[1][3].
*   JavaScript – Handling user input and API data[1][3].
*   OpenWeather API – API to fetch weather data[1][2].

## Installation
To run the app locally, follow these steps:

1.  Clone the repository:
    ```
    git clone https://github.com/your-username/weather-app.git
    ```
2.  Navigate to the project directory:
    ```
    cd weather-app
    ```
3.  Open the `index.html` file in your browser:
    ```
    open index.html  # macOS
    # or
    start index.html # Windows
    ```

## Usage
1.  Enter a city name in the search box[2][4].
2.  Click on the search button to fetch the weather data[2][4].
3.  The weather data will be displayed, including the temperature, description, humidity, and wind speed[2][9].

## API Key
To use this app, you need an API key from OpenWeather. Here’s how to get one:
1.  Go to [OpenWeather](https://openweathermap.org/)[2][4].
2.  Sign up for an account and generate your free API key[4].
3.  Replace the placeholder in the JavaScript file:
    ```
    const APIKey = "...........";
    ```
