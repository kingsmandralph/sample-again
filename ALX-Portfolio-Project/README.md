# ALX Portfolio Project - Simple weatherapp using openweather API
-----------------------------------------------------------------------

## Summary:
This weatherapp project, simply brings to light the use of Application Programming Interface, using the OpenWeather API to gather real-time weather information about a particular place.

### Requirements needed to replicate:
- A free account on [*OpenWeather*](https://openweathermap.org/)
- A free service API plan
- Your API endpoint
- Your location coordinates, which can be gotten [**HERE**](https://mylocation.org/)
- Your preferred IDE

To get instructions on how to activate your API key to get it up and running, click this [link](https://docs.google.com/document/d/1rCFrchixJvPXdDpcnRQycQsqqOFd0uBQn_8qokXeTjg/edit?usp=sharing) 😇


#### Simple explanation of Kingsman999 weatherapp

1. Firstly, we have the HTMl boilerplate, which contains a `<link>` tag to link our css file and `<script>` tag, to connect our Javascript file to our html file
2. In the `<body>` tag, we'd see the onload attribute which calls our `loadSite()` function in our Javascript file
3. Next, to our Js file; we can see that we started by initiating two variables; longitude and latitude. 
    - Essentially, when the browser gets the user location, it is in form of longitude and latitude
4. Next is the `loadSite()` function; which automatically requests user location once the HTML has been loaded
5. Then we would initialize the `url` variable using our API endpoint, which contains our API key and location coordinates
6. Then using the `fetch()` method, we will be able to get a response from the API Service Provider. 
7. The `then()` function is required as our `fetch` method takes a lot of time before it reaches completion due to its asynchronous property.
8. Then the API would return a response and we'd convert it to a JSON format.
9. We can access the weather descriptor by using `json.weather[0].name` and it will return names like "Rain", "Fair", "Clouds" etc. 
    - Using a switch statement, we can check through the various test cases to determine which image we want to switch to, depending on the weather descriptor.


## *Sample Preview of the WeatherApp*
![Image](https://github.com/kingsmandralph/simple-api-weatherapp/blob/main/weather-image.png)





