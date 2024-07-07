# Project Number 6: WeatherPy and VacationPy

## Summary
This project is divided into two main parts: WeatherPy and VacationPy, each with specific deliverables.

## Part 1: WeatherPy
In WeatherPy, the goal is to create a Python script that visualizes the weather for over 500 cities at varying distances from the equator. 
This will be achieved using the citipy Python library, the OpenWeatherMap API, and problem-solving skills to model weather conditions across different cities.

### Instructions
- **WeatherPy.ipynb**: Use the provided Jupyter notebook to develop your solution.
- **Generate Random Coordinates**: The starter code includes functionality to generate random geographic coordinates and find the nearest city for each.
- **Retrieve Weather Data**: Use the OpenWeatherMap API to gather weather data for the generated list of cities.

### Requirements
**Create Visualizations to Showcase Weather Variables vs. Latitude**:
- Retrieve weather data and create scatter plots for:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed

**Compute Linear Regression for Each Relationship**:
- Separate plots into Northern Hemisphere and Southern Hemisphere.
- Create linear regression plots including the regression line, formula, and r² values for:
  - Temperature vs. Latitude (Northern and Southern Hemisphere)
  - Humidity vs. Latitude (Northern and Southern Hemisphere)
  - Cloudiness vs. Latitude (Northern and Southern Hemisphere)
  - Wind Speed vs. Latitude (Northern and Southern Hemisphere)

## Part 2: VacationPy
In VacationPy, you will leverage your weather data skills to plan future vacations using Jupyter notebooks, the geoViews Python library, and the Geoapify API.

### Instructions
- **VacationPy.ipynb**: Open the provided Jupyter notebook and follow the steps to complete the tasks.
- **Map Visualization**: Use the Geoapify API and geoViews to create map visualizations.

### Requirements
**Create a Map with Humidity Data**:
- Display a map showing each city in the `city_data_df` DataFrame, with the size representing the city's humidity.

**Narrow Down Ideal Weather Conditions**:
- Filter `city_data_df` to find cities meeting specific weather conditions, such as:
  - Max temperature between 21°C and 27°C
  - Wind speed less than 4.5 m/s
  - Zero cloudiness

**Hotel Search Using Geoapify API**:
- Create a `hotel_df` DataFrame to store city, country, coordinates, and humidity.
- For each city, use the Geoapify API to find the nearest hotel within 10,000 meters and add this information to the DataFrame.

**Enhanced Map with Hotel Information**:
- Add the hotel name and country to the hover message for each city on the map.

### Hints and Considerations
- Study the OpenWeatherMap API to understand the required endpoints and data structure.
- Use the citipy library to find the nearest city for given coordinates.
- Ensure you cover a wide range of latitudes and longitudes to avoid biased data.
- Create functions to automate the plotting process for different weather variables.
- Limit the number of API calls to avoid exceeding usage limits.

### Requirements

#### Part 1: WeatherPy
**Create Visualizations**:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

**Compute Linear Regression**:
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

#### Part 2: VacationPy
- Map with Humidity Data.
- Ideal Weather Conditions.
- Hotel Search with Geoapify API.
- Enhanced Map with Hotel Information.
