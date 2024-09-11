# React Weather

This is my first web app built using ReactJS, and is a weather app built using ReactJS and uses OpenWeatherMap and GeoDB APIs for autocompletion and weather data.

I used npx to create the react app and used two other packages: react-accessible-accordion (for the dropdown area for the upcoming days) and react-select-async-paginate (to allow for the autocompletion in the search bar).

## Features 

When you type in a city into the search bar, it will autocomplete the city name and display the cities that match the given name:
![SearchDropDown](/public/pictures/SearchBarAutofill.png)

After you pick the city, the weather and some related info will be displayed:
![DisplayWeather](/public/pictures/DisplayWeather.png)

Additionally, the weather forecast of the week will be displayed, and when you click on a certain day, the weather information of that day will be shown:
![OpenDropDownOfWeather](/public/pictures/OpenDropDown.png)

For more information on the weather of the city, I've created a button that will take you to a more detailed weather information app.