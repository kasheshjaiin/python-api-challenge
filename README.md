# Vacation Planner

Welcome to Vacation Planner! This project is designed to help you plan your next vacation by providing recommendations for cities with suitable weather conditions and nearby hotels.

## Project Overview

- **Objective**: The main goal of this project is to assist users in planning their vacations by suggesting cities with pleasant weather conditions and nearby accommodation options.
- **Functionality**: The application leverages data from the OpenWeatherMap API to analyze weather conditions for cities worldwide, including temperature, humidity, cloudiness, and wind speed. It also utilizes the Geoapify API to search for nearby hotels in selected cities.
- **User Interaction**: Users can specify their desired weather conditions, such as temperature and humidity ranges, and the application will recommend cities that meet those criteria. Additionally, it provides information about nearby hotels to facilitate accommodation booking.
- **Dependencies**: This project relies on various Python libraries, including Matplotlib, Pandas, NumPy, and Requests, for data analysis and API interactions.

## How It Works

1. **Weather Data Analysis**: The application fetches weather data for cities using the OpenWeatherMap API. It analyzes parameters like temperature and humidity to identify cities with suitable weather conditions.
2. **Hotel Search**: After selecting potential cities, the application uses the Geoapify API to search for nearby hotels. It provides users with options for accommodation in their chosen destinations.
