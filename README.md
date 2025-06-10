# Simple Weather App

A minimalist and interactive web application that displays current weather conditions for a specified city. Built using HTML, CSS, and vanilla JavaScript, this app fetches real-time weather data from a public API.

## Features

* **Current Weather Display:** Shows temperature, weather description, humidity, and wind speed.
* **City Search:** Allows users to search for weather conditions in any city worldwide.
* **Responsive Design:** Adapts to various screen sizes for optimal viewing on desktops, tablets, and mobile devices.
* **Clean Interface:** Simple and intuitive design for ease of use.

## Technologies Used

* **HTML5:** Structure of the web page.
* **CSS3:** Styling and layout for an appealing user interface.
* **JavaScript (Vanilla JS):** Handles API requests, data processing, and dynamic content updates.
* **OpenWeatherMap API:** Provides real-time weather data. (You'll need to sign up for a free API key).

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/simple-weather-app.git](https://github.com/your-username/simple-weather-app.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd simple-weather-app
    ```
3.  **Get an API Key:**
    * Go to [OpenWeatherMap](https://openweathermap.org/api) and sign up for a free account.
    * Once logged in, navigate to the "API keys" tab to generate your API key.
4.  **Configure API Key:**
    * Open `script.js` in your text editor.
    * Locate the line where the `apiKey` variable is declared (e.g., `const apiKey = "YOUR_API_KEY";`).
    * Replace `"YOUR_API_KEY"` with the API key you obtained from OpenWeatherMap.
5.  **Open `index.html`:**
    * Simply open the `index.html` file in your web browser.

## Project Structure

.
├── index.html       // Main HTML file
├── style.css        // CSS for styling the app
└── script.js        // JavaScript for fetching and displaying weather data
