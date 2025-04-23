# REST-API-CLIENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: GANARAJU SANDEEP VARMA

*INTERN ID*: CT04WT31

*DOMAIN* : JAVA PROGRAMMING

*DURATION* : 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR  

*DESCRIPTION*:
WeatherAPIData is a Java-based console application that allows users to retrieve real-time weather data for any city around the world using public APIs provided by Open-Meteo. The primary purpose of this application is to demonstrate how Java can interact with web services through HTTP requests and handle JSON responses using the json-simple library. When a user enters the name of a city, the application connects to the Open-Meteo Geocoding API to retrieve the geographical coordinates (latitude and longitude) of the specified city. These coordinates are then used to request the current weather conditions from the Open-Meteo Forecast API. The application displays relevant weather information such as the current temperature in Celsius, relative humidity percentage, wind speed at 10 meters above ground level, and the exact timestamp of the recorded data.

The program runs in a loop, allowing users to make multiple city queries without restarting the application. Users can exit the application at any time by typing "No" when prompted for a city name. The interface is straightforward and text-based, making it suitable for command-line environments or educational settings where users can focus on understanding the flow of API data without needing a graphical interface. Behind the scenes, the application uses Java’s HttpURLConnection class to perform GET requests, processes the incoming response through input streams, and parses JSON content into Java data structures using the JSON.simple library.

This project also emphasizes the importance of clean code structure and modularization. Functions are organized in a way that separates concerns: one method handles API communication, another processes the input/output, and others deal with parsing and displaying the data. Proper exception handling ensures that the program doesn’t crash due to issues like network errors, invalid city names, or unexpected JSON structures. When an API call fails or returns no results, the application notifies the user and continues running smoothly, allowing them to try again.

WeatherAPIData is a practical tool for learning how to connect Java applications to real-time external data sources. It shows how to manage HTTP connections, parse JSON, and structure a Java project that involves asynchronous web interactions. The Open-Meteo APIs used are free and do not require an API key, making this project accessible for beginners and useful for teaching purposes. Whether you are a student exploring Java networking and JSON parsing, or a developer looking for a base template to build a more advanced weather app, this project serves as a great starting point.

In summary, WeatherAPIData is a functional, beginner-friendly Java application that showcases real-time weather data retrieval by integrating with web APIs. It combines core programming concepts such as user input, network communication, error handling, and data parsing into one cohesive project. It can easily be extended to include more detailed weather forecasts, a GUI interface, or support for multiple results per city. This makes it a flexible and educational example for anyone looking to enhance their Java skills through hands-on, real-world projects.

#output

![Image](https://github.com/user-attachments/assets/42cacfa1-a9b9-471f-8f3f-df3e6bfcc933)
