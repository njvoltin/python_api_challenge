Overview
This project uses Python, Jupyter Notebook, and several APIs to analyze weather patterns across cities and create visualizations for planning vacations. The project is divided into two main parts:

WeatherPy: Analyzing weather data for over 500 cities worldwide to study the relationship between weather variables and geographic latitude.
VacationPy: Using weather data to identify ideal vacation locations and mapping nearby hotels using Geoapify.

Technologies Used
Python: Main programming language.
Jupyter Notebook: For organizing and running the code.
APIs:
OpenWeatherMap API: To retrieve weather data.
Geoapify API: To locate nearby hotels for vacation planning.

Libraries:
Pandas: Data manipulation and analysis.
Matplotlib: For creating scatter plots and visualizations.
hvPlot: Interactive map visualizations.
GeoViews: Geographical data plotting.
SciPy: For calculating linear regression.
Citipy: Finding nearest cities based on random geographic coordinates.
Features
Part 1: WeatherPy
Generate Random Cities and Retrieve Weather Data:

Generate random geographic coordinates.
Use the Citipy library to identify the nearest city.
Retrieve weather data using the OpenWeatherMap API.
Visualize Relationships Between Latitude and Weather Variables:

Create scatter plots for:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Linear Regression Analysis:

Split data into Northern and Southern Hemispheres.
Perform linear regression to analyze:
Temperature vs. Latitude
Humidity vs. Latitude
Cloudiness vs. Latitude
Wind Speed vs. Latitude
Display regression lines, equations, and r^2 values

Part 2: VacationPy
Create a Map with Weather Data:

Plot cities with points sized by their humidity values.
Identify Ideal Vacation Locations:

Filter cities based on ideal weather conditions:
Maximum temperature: 21–27°C
Wind speed: < 4.5 m/s
Cloudiness: 0%
Locate Hotels:

Use the Geoapify API to find nearby hotels within 10,000 meters of the selected cities.
Store city, country, coordinates, humidity, and hotel names in a DataFrame.

Display cities with hover information including:
City name
Country
Hotel name

The Jupyter Notebooks can be found in the starter code file.
