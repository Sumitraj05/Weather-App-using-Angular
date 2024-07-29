# Weather-App-using-Angular
<h2>Overview</h2>
    <p>The Weather App is a web application built using Angular that allows users to search for any location and retrieve comprehensive weather conditions. The app provides real-time weather data, including temperature, humidity, UV index, wind status, visibility, air quality, and sunrise and sunset times. Users can also view detailed weather forecasts for today and the upcoming week.</p>

  <h2>Features</h2>
  <ul>
      <li>Temperature: Displays temperature in both Celsius and Fahrenheit.</li>
      <li>Humidity: Shows the humidity levels.</li>
      <li>UV Index: Indicates the UV index.</li>
      <li>Wind Status: Provides information about wind speed and direction.</li>
      <li>Sunrise and Sunset Times: Shows the times of sunrise and sunset.</li>
      <li>Visibility: Indicates visibility levels.</li>
      <li>Air Quality: Displays air quality information.</li>
      <li>Weather Forecast: Provides detailed weather data for today and the week ahead.</li>
      <li>Today's Highlights: Offers a summary of key weather highlights for the day.</li>
  </ul>

  <h2>Technologies Used</h2>
  <ul>
      <li>Angular: Framework for building the application.</li>
      <li>RapidAPI WeatherAPI Dojo: API used to fetch weather data.</li>
      <li>Angular FontAwesome: Icons for enhanced aesthetics and interactivity.</li>
      <li>HTML, CSS, TypeScript: Core web technologies used in the project.</li>
  </ul>

  <h2>Project Structure</h2>
  <ul>
      <li>src/app: Contains the main application code.</li>
      <ul>
          <li>left-container: Component for the left section of the app.</li>
          <li>right-container: Component for the right section of the app.</li>
          <li>models: Contains the models used in the application.</li>
          <li>services: Contains the services for API calls and data handling.</li>
          <li>environment: Contains environment variables and configurations.</li>
      </ul>
      <li>assets: Contains static assets like images and stylesheets.</li>
      <li>environments: Configuration files for different environments (e.g., development, production).</li>
  </ul>

  <h2>Installation</h2>
  <p>Clone the repository:</p>
  <pre><code>git clone https://github.com/your-username/weather-app.git
cd weather-app</code></pre>

  <p>Install the dependencies:</p>
  <pre><code>npm install</code></pre>

  <p>Add your RapidAPI WeatherAPI Dojo API key:</p>
  <p>Create a file named <code>environment.ts</code> in the <code>src/environments</code> folder.</p>
  <p>Add the following code to the file:</p>
  <pre><code>export const environment = {
  production: false,
  apiKey: 'YOUR_API_KEY_HERE'
};</code></pre>

  <p>Run the application:</p>
  <pre><code>ng serve</code></pre>

  <p>Open your browser and navigate to <a href="http://localhost:4200">http://localhost:4200</a>.</p>

  <h2>Usage</h2>
  <ul>
      <li>Enter a location in the search bar to get the current weather conditions and forecast.</li>
      <li>View the temperature, humidity, UV index, wind status, visibility, air quality, and sunrise and sunset times.</li>
      <li>Check the detailed weather forecast for today and the upcoming week.</li>
      <li>View today's weather highlights.</li>
  </ul>

  <h2>Learning Experience</h2>
  <p>This project has been an incredible learning experience, allowing me to gain valuable skills in web development, API integration, and user interface design. I'm excited to continue honing my skills and taking on new challenges.</p>

  <h2>Contributing</h2>
  <p>Contributions are welcome! Please feel free to submit a Pull Request.</p>

  <h2>License</h2>
  <p>This project is licensed under the MIT License.</p>

  <h2>Acknowledgements</h2>
  <p>Thanks to RapidAPI for providing the WeatherAPI Dojo API.</p>
  <p>Special thanks to the Angular team for their excellent framework and documentation.</p>

  <h2>Project Demonstration Video</h2>
  <p><a href="https://www.linkedin.com/posts/sumit-raj-tiwari-855338251_angular-weatherapp-webdevelopment-activity-7223766204157444096-72x4?utm_source=share&utm_medium=member_desktop">Project Demonstration Video</a></p>
