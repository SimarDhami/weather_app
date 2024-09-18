Weather App GUI ☀️🌧️

The Weather App is a Java-based application that allows users to access real-time weather information for any specified location. It fetches data from an external weather API and presents key weather details such as temperature, weather conditions, humidity, and wind speed. The app features a graphical user interface (GUI) where users can input a location and view up-to-date weather information.

Technologies Used
Java 18: Core programming language for building the app.
JSON Simple: Used for parsing and reading JSON data from the weather API.
HTTPURLConnection: Java's built-in library for making HTTP requests to external APIs.

Class Summaries
1. AppLauncher
Description: Serves as the entry point for the application.
Functionality: Initializes the GUI and opens the main application window.

2. WeatherAppGui
Description: Handles the graphical user interface (GUI) for the Weather App.
Functionality: Manages the layout and components like text fields, labels, and buttons. It provides a user-friendly interface to input a location and display the corresponding weather information.

3. WeatherApp
Description: Contains the backend logic to fetch weather data from the external API.
Functionality: Retrieves location coordinates, fetches weather data, and converts weather codes into human-readable formats. This class bridges the gap between the GUI and the external data source, ensuring accurate weather information is displayed to users.
