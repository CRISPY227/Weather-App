Weather App

This weather application allows users to check the current weather of any city by simply entering its name. The app fetches data from the OpenWeather API, displays the temperature, humidity, weather description, and an appropriate weather emoji. A Project done to further my JavaScript Knowledge

Key Features:
- **Real-time Data Fetching:** The app uses JavaScript’s `fetch()` and `async/await` for fetching live weather data from the OpenWeather API based on user input.
- **Weather Information Display:** Once the data is received, the app dynamically displays the city’s temperature (converted from Kelvin to Fahrenheit), humidity, description, and an emoji representing the current weather condition.
- **Error Handling:** If the city input is invalid or the API call fails, an error message is displayed, guiding the user to correct the input.
- **Responsive Design:** The app adjusts seamlessly across devices, with clear typography and well-structured content for readability.
  
### JavaScript Concepts & Techniques:
- **Async/Await & Fetch API:** The app makes asynchronous requests to retrieve weather data without blocking the UI. `async/await` makes the code more readable and easier to work with.
- **Object Destructuring:** The weather data is extracted using both object and array destructuring, demonstrating a clean and efficient way to access nested data.
- **Dynamic DOM Manipulation:** JavaScript is used to create and style elements on the fly, updating the DOM with relevant weather details or error messages.
- **Weather Emojis:** The app uses a switch statement to return different weather emojis based on the API's weather condition ID, enhancing the visual appeal of the app.

