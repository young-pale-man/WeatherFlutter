# Weather🌦

Flutter weather app project. Includes working with device geolocation and API technologies.

## Technologies🔧

#### - Flutter
#### - Geolocator
#### - API
#### - Async Functions
#### - Open Weather Map
#### - HTTP
#### - Dart.Convert
#### - JSON

## Interface💻

The application is a screen displaying the current location of the device (locality), 
the weather there and the air temperature. There is a geolocation update button and a 
button to go to the weather search screen in a locality by the entered name.

## Functionality🕹

For the application to work, the user must provide permission to use the device's geolocation. 
This can be done when logging into the application for the first time or using the device settings.

When entering the application, the user is greeted by a “load spinner”, which rotates until the 
asynchronous function receives the current location of the device. The speed of this function 
directly depends on the connection speed of the device.

After successfully obtaining the device's geolocation, the application displays a screen that 
displays the current temperature, weather, comment about the weather, and weather emoji.

The application receives data for these fields using the API from the Open Weather website. 
By sending a "get" request and converting the received data into .json, the variables are assigned 
values in accordance with pre-specified indices.

There is a button with a map image on the screen, which performs the same function that is 
performed automatically when entering the application - it receives the geolocation of the device 
and displays data on the current location. This option is useful when changing the geolocation of 
the device, for example, if the user is in transit.

There is also a button to go to the screen with a city search field. By entering the name correctly, 
the user receives the same weather data, but according to the geolocation he entered.

The result is a simple weather app that demonstrates working with device geolocation, permissions, 
APIs, and conversion to .json⛅️

## Possible future improvements⬆️

#### - New interface
#### - Validation when searching for a city
#### - More accurate work with geolocation
#### - More weather data
