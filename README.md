# MuleSoft Weather API

This project demonstrates a MuleSoft API that provides weather information by integrating with the OpenWeatherMap API. The API retrieves weather data from OpenWeatherMap and returns it to the client.

## Prerequisites

- MuleSoft Anypoint Studio
- A valid OpenWeatherMap API key. You can register for a free API key at [OpenWeatherMap](https://openweathermap.org/api).

## Configuration

Before running the application, you will need to update the `appid` query parameter in the HTTP Request configuration with your own OpenWeatherMap API key. Follow these steps:

1. Open the project in MuleSoft Anypoint Studio.
2. Locate the HTTP Request component that calls the OpenWeatherMap API.
3. Replace the placeholder in the `appid` query parameter with your personal API key.

