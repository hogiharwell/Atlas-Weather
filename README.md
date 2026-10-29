# Atlas Weather
Responsive worldwide weather dashboard built with plain HTML, CSS, and JavaScript. No framework, build step, or API key required for Open-Meteo's non-commercial free API.

## Features
- Worldwide city search with disambiguated results
- Current model-based weather, seven-day forecast, humidity, wind and feels-like temperature
- Selected cities across seven geographic regions, including Antarctica
- Fahrenheit / Celsius toggle, opt-in device location, manual refresh and 15-minute refresh while visible
- Loading, empty-search and API-error states

All asset links are relative, so project repositories under a subpath work. No credentials belong in the repository. The `.openai/` folder in this source checkout is for the optional ChatGPT Sites deployment and is not needed for GitHub Pages.

## Data and licensing
Forecast and geocoding: https://open-meteo.com/ and https://open-meteo.com/en/docs/geocoding-api . Keep visible attribution. Current conditions are weather-model estimates, not instantaneous station observations. The displayed time is local to the selected location; cards refresh every 15 minutes while the page is visible. Regional cities are representative, not a complete listing of every location.

Check https://open-meteo.com/en/terms and current API limits before commercial deployment; commercial use may require a paid service. Browser requests expose users' IP addresses and selected coordinates to the data provider. Device location is requested only when the visitor clicks the location button. This app stores no location history.
