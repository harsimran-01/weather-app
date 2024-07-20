# weather-app

README
Weather App
This is a simple weather application that displays the current weather conditions for a specified city. The app uses the OpenWeatherMap API to fetch weather data and updates the UI accordingly.

Features
Search for a city's weather.
Displays temperature, humidity, and wind speed.
Shows weather icons based on current weather conditions (e.g., clouds, clear, rain, snow, drizzle, mist).
Technologies Used
HTML
CSS
JavaScript
OpenWeatherMap API
Setup and Installation
Clone the repository:

sh
Copy code
git clone <repository-url>
Navigate to the project directory:

sh
Copy code
cd <project-directory>
Open index.html in your browser:

sh
Copy code
open index.html
Code Structure
index.html: The main HTML file that contains the structure of the application.
Inline CSS: Contains the styles for the application within the <style> tag in the index.html file.
Inline JavaScript: Contains the logic for fetching weather data and updating the UI within the <script> tag in the index.html file.
HTML
The index.html file contains the basic structure of the application including:

A search input field for the user to enter a city name.
A button to trigger the weather search.
Sections to display the weather information including temperature, city name, humidity, and wind speed.
CSS
The CSS is written within a <style> tag inside the index.html file. It includes styles for:

Centering the content on the page.
Styling the search input field and button.
Displaying the weather information with appropriate colors and font sizes.
Background gradient and rounded corners for the main container.
JavaScript
The JavaScript is written within a <script> tag inside the index.html file. It includes:

An API key and URL to fetch weather data from OpenWeatherMap.
Functions to handle the weather data and update the UI.
Event listeners for the search button to trigger the weather search based on the user input.
Usage
Search for a City:

Enter the city name in the search input field.
Click the search button.
The application will fetch and display the weather data for the specified city including temperature, humidity, and wind speed, and will update the weather icon accordingly.

Initial Weather Check:

The app performs an initial weather check for Bangalore when it loads.
API Integration
The application uses the OpenWeatherMap API to fetch weather data. Make sure to replace the apiKey variable with your own API key from OpenWeatherMap.

javascript
Copy code
const apiKey = "your_api_key_here";
Images
The application uses several images for displaying weather icons. Ensure the images are placed in an images directory within the project.

Note
Ensure an active internet connection to fetch data from the OpenWeatherMap API.
The API key provided in the code is for demonstration purposes. Use your own API key for production.
License
This project is licensed under the MIT License.


https://github.com/user-attachments/assets/2ab190b2-69be-4d38-a3e4-4100a14b44c5


