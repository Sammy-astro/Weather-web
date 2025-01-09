# Weather App

This is a simple weather app that fetches and displays the current weather information for a given city. The app uses the OpenWeatherMap API to fetch weather data and dynamically updates the UI.

---

## **Features**
- Search for weather information by city name.
- Displays:
  - Current temperature
  - Humidity
  - Wind speed
  - Weather condition icon
- Handles invalid city names with an error message.

---

## **File Structure**

- `index.html`: Contains the structure of the weather app.
- `style.css`: Styles for the app.
- `config.js`: Stores the API key. This file is excluded from version control.
- `config.example.js`: Provides a template for the `config.js` file with placeholder values for the API key.

---

## **Setup Instructions**

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Install a live server (if not already installed) to serve the app locally. For example:
   ```bash
   npm install -g live-server
   ```

4. Copy `config.example.js` to `config.js` and replace `YOUR_API_KEY_HERE` with your OpenWeatherMap API key:
   ```bash
   cp config.example.js config.js
   ```

5. Start the live server:
   ```bash
   live-server
   ```

6. Open your browser and navigate to the URL provided by the live server (e.g., `http://127.0.0.1:8080`).

---

## **How to Use**
1. Enter a city name in the search box.
2. Click the search button.
3. The app will display the weather information or show an error if the city name is invalid.

---

## **API Key Management**
- Do **NOT** share your `config.js` file publicly, as it contains your API key.
- Use `config.example.js` as a reference for collaborators to add their own API key.

---

## **Credits**
- Weather data powered by [OpenWeatherMap](https://openweathermap.org/).
- Icons sourced from custom local images folder.

---

## **Screenshots**
![App Preview](images/preview.png)

---

## **License**
This project is licensed under the MIT License. Feel free to use and modify it as needed.

