# bsd-weather-app (Weather App)

## Requirement

* Get your free API key from OpenWeather API, (or any similar weather API you can find). Study the documentation before starting implementation.
* The website looks similar to the design (Desktop and Mobile) and is available for users through a link.
* On the initial page load, weather for either hardcoded city (e.g. London) is shown or geolocation logic checks which city should be presented.
* Users can check the weather of cities using the search bar, request to the API should trigger after entering a minimum of 2 characters and be debounced to prevent too many requests at once. (no enter click, listen to keypress and fetch data after e.g. 300 milliseconds delay, try to avoid fetch on the first character typed in)
* When users use the search bar, current weather should be replaced by the search result, if the city couldn't be found, an appropriate message to the user shall be displayed.
* Users can change between Celsius and Fahrenheit temperatures to get more adequate results.
* Handle loading and errors in the code appropriately. (handle error first, then loading, then data)

## Additional Requirements

* To avoid working on a real API and burning its daily limits, implement a mock server first (try to recreate original schema/data format), code the app, and when it'll be ready switch to the real Weather API (e.g. OpenWeather) for final testing if all works nicely together.
* Implement more fields from the API, explore, discover what's available and make it as robust as it's possible. Use all the data! 🔥
* Add API tests to your code, using e.g. jest.
* Add e2e tests to your code, using e.g. cypress.