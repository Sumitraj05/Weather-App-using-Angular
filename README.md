# Weather-App-using-Angular
Overview
The Weather App is a web application built using Angular that allows users to search for any location and retrieve comprehensive weather conditions. The app provides real-time weather data, including temperature, humidity, UV index, wind status, visibility, air quality, and sunrise and sunset times. Users can also view detailed weather forecasts for today and the upcoming week.

Features
Temperature: Displays temperature in both Celsius and Fahrenheit.
Humidity: Shows the humidity levels.
UV Index: Indicates the UV index.
Wind Status: Provides information about wind speed and direction.
Sunrise and Sunset Times: Shows the times of sunrise and sunset.
Visibility: Indicates visibility levels.
Air Quality: Displays air quality information.
Weather Forecast: Provides detailed weather data for today and the week ahead.
Today's Highlights: Offers a summary of key weather highlights for the day.
Technologies Used
Angular: Framework for building the application.
RapidAPI WeatherAPI Dojo: API used to fetch weather data.
Angular FontAwesome: Icons for enhanced aesthetics and interactivity.
HTML, CSS, TypeScript: Core web technologies used in the project.
Project Structure
src/app: Contains the main application code.
left-container: Component for the left section of the app.
right-container: Component for the right section of the app.
models: Contains the models used in the application.
services: Contains the services for API calls and data handling.
environment: Contains environment variables and configurations.
assets: Contains static assets like images and stylesheets.
environments: Configuration files for different environments (e.g., development, production).
<a href="https://www.linkedin.com/posts/sumit-raj-tiwari-855338251_angular-weatherapp-webdevelopment-activity-7223766204157444096-72x4?utm_source=share&utm_medium=member_desktop" > Project Demostration Vedio </a>
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/weather-app.git
cd weather-app
Install the dependencies:

bash
Copy code
npm install
Add your RapidAPI WeatherAPI Dojo API key:

Create a file named environment.ts in the src/environments folder.
Add the following code to the file:
typescript
Copy code
export const environment = {
  production: false,
  apiKey: 'YOUR_API_KEY_HERE'
};
Run the application:

bash
Copy code
ng serve
Open your browser and navigate to http://localhost:4200.

Usage
Enter a location in the search bar to get the current weather conditions and forecast.
View the temperature, humidity, UV index, wind status, visibility, air quality, and sunrise and sunset times.
Check the detailed weather forecast for today and the upcoming week.
View today's weather highlights.
Learning Experience
This project has been an incredible learning experience, allowing me to gain valuable skills in web development, API integration, and user interface design. I'm excited to continue honing my skills and taking on new challenges.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License.

Acknowledgements
Thanks to RapidAPI for providing the WeatherAPI Dojo API.
Special thanks to the Angular team for their excellent framework and documentation.
