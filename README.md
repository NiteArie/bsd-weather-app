# bsd-weather-app (Weather App)

## Requirement

* Get your free API key from OpenWeather API, (or any similar weather API you can find). Study the documentation before starting implementation.
* The website looks similar to the design (Desktop and Mobile) and is available for users through a link.
* On the initial page load, weather for either hardcoded city (e.g. London) is shown or geolocation logic checks which city should be presented.
* Users can check the weather of cities using the search bar, request to the API should trigger after entering a minimum of 2 characters and be debounced to prevent too many requests at once. (no enter click, listen to keypress and fetch data after e.g. 300 milliseconds delay, try to avoid fetch on the first character typed in)
* When users use the search bar, current weather should be replaced by the search result, if the city couldn't be found, an appropriate message to the user shall be displayed.
* Users can change between Celsius and Fahrenheit temperatures to get more adequate results.
* Handle loading and errors in the code appropriately. (handle error first, then loading, then data)