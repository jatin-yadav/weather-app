
# Weather APP

Weather App is a simple web application that allows users to check the current weather conditions for a specific city. It's built using HTML, CSS, and JavaScript and integrates with a weather API to fetch and display weather data.

## Demo
visit: (https://jatin-yadav.github.io/weather-app/)

<img src="https://github.com/jatin-yadav/weather-app/blob/main/images/example.png"></img>
## Features
Enter a city to view current weather information.
Display location, temperature, description, and weather icon.
Easy-to-use and responsive design.

## Prerequisites
Before you begin, ensure you have met the following requirements:

A code editor for making modifications.
An API key from a weather service provider (e.g., OpenWeatherMap).

## Usage

1. Open the Weather App in your web browser.

2. Enter a city name in the input field.

3. Click the "Search" button or "Enter key".

4. The app will fetch and display the current weather conditions for the entered city.

## API Integration
The Weather App integrates with a weather API service. You can obtain an API key from the service of your choice (e.g., OpenWeatherMap) and use it to fetch weather data in script.js.
## Installation
Clone the repository:

```bash
git clone https://github.com/jatin-yadav/weather-app.git
```
Open a JavaScript file (script.js) and replace 'YOUR_API_KEY' with your actual API key.

Open index.html in a web browser to use the Weather App.
    
# How to Develop

## 1. Set up your project:

Create a project folder and create three files: index.html, style.css, and script.js.

## 2. HTML Structure (index.html):
Create basic HTML Structure according to the design of your app.

## 3. Styling (style.css):
Now style your app as you like.

## 4. JavaScript Functionality (script.js):

The JavaScript code for a Weather App typically involves handling user interactions, making API requests, and updating the DOM with weather information. I'll break down the key components and concepts involved in a weather app's JavaScript code.

1. Selecting DOM Elements: These lines of code select various HTML elements by their IDs and classes. These elements are used to display the weather information and capture user input.

2. Event Listener: An event listener is attached to the "Search" button. It listens for a click/enter event and executes the code inside the event handler when the button is clicked.

3. API Request Setup:

The user's input (city name) is retrieved from the search Input element.
An API key is defined. You should replace 'YOUR_API_KEY' with your actual API key from a weather service provider.
The API endpoint is constructed with the API key and the city name.

4. Making an API Request: The Fetch API is used to make an HTTP request to the weather API. The fetch method returns a Promise that resolves to the response from the API.

5. Handling API Response: The response from the API is handled. It's assumed that the API returns JSON data. The JSON data is extracted from the response.

The weather data (location name, temperature in Celsius, weather description, and a the weather condition) is extracted from the JSON response.

6. Updating the DOM: The DOM elements are updated with the extracted weather data. This includes updating the location name, temperature, description, and displaying the weather icon using an <img> element.

7. Error Handling: Response status is used to handle errors that may occur during the API request. It logs an error message to the console, and display an error message to the user.
## Contact
If you have any questions or feedback, please feel free to contact me:

Jatin Yadav (jatinyadav.dev@gmail.com)
