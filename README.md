# Simple Weather Web App
Weather web app widget with one search box where user can enter the city name and get the weather information of the particular city, using `HTML, CSS, JS, OpenWeather API`  
Obtained the current weather data from Fess API fey from OpenWeatherMap and display the weather information according to the city on our website or app.:
- Temperature
- Weather condition
- Humidity
- Wind Speed 
We will display the weather info on website from Free API using JavaScript.  

![searchSD](images/search2.jpg)

Workflow:
1. Structure HTML
2. Style CSS
3. JS API Call
4. Finishing Details

## OpenWeather API
OpenWeatherMap is an online service that provides global weather data via API, including current weather data, forecasts, nowcasts and historical weather data for any geographical location. The company provides a minute-by-minute hyperlocal precipitation forecast for any location.
[Current weather data](https://openweathermap.org/current#name)

### HOME / API / Current weather
Other features
    > Built-in geocoding
        > Built-in API request by city name

### Built-in API request by city name
You can call by city name or city name, state code and country code. Please note that searching by states available only for the USA locations.

**API call**  
`https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}`

### Format
Response format is JSON by default. To get data in XML format just set up  
mode = xml.

![init](images/init.jpg)
![searchBako](images/search1.jpg)
