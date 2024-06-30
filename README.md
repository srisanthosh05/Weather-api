# Weather-api
**Overview:**
The Weather API provides developers with access to real-time weather data, including current conditions, forecasts, and historical weather information. It is designed to be easy to integrate into applications, websites, and other digital services.

**Key Features:**
Current Weather Data: Get real-time weather conditions such as temperature, humidity, wind speed, and more for any location.
Weather Forecasts: Access detailed forecasts for the next 7, 14, or even 30 days, including daily and hourly predictions.
Historical Weather Data: Retrieve weather data from past dates to analyze trends and patterns.
Weather Alerts: Receive notifications for severe weather events such as storms, hurricanes, and extreme temperatures.
Global Coverage: Access weather data for any location around the world, including cities, towns, and rural areas.
Multiple Units: Get data in various units (e.g., metric, imperial) to suit different user preferences.
API Endpoints:
**Current Weather:**
Endpoint: /current
Parameters: location (string), units (optional, string)
Example Request: GET /current?location=London&units=metric
**Weather Forecast:**
Endpoint: /forecast
Parameters: location (string), days (optional, integer), units (optional, string)
Example Request: GET /forecast?location=New York&days=7&units=imperial
**Historical Weather:**
Endpoint: /historical
Parameters: location (string), date (string, format: YYYY-MM-DD), units (optional, string)
Example Request: GET /historical?location=Paris&date=2023-06-15&units=metric
**Weather Alerts:**
Endpoint: /alerts
Parameters: location (string)
Example Request: GET /alerts?location=Tokyo
