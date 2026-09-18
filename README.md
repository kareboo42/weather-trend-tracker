HEAD
﻿# Weather Trend Tracker

# Weather Trend Tracker
45dc94d3273a9c0c276e9474cdb61d7c84e8bd0a

A small Python project that pulls live weather data from a public API, cleans and structures it, and visualizes it — built to practice core data analyst skills: API integration, data cleaning, and reporting.

## What it does

<<<<<<< HEAD
1. Calls the OpenWeatherMap API to fetch current weather data for multiple cities
2. Parses the raw (nested, unstructured) JSON response and extracts the relevant fields
3. Loads the cleaned data into a pandas DataFrame and exports it to a structured CSV
4. Generates a color-coded bar chart comparing temperatures across cities using matplotlib

## Skills demonstrated

- API integration - authenticated requests, query parameters, handling JSON responses
- Data cleaning - converting unstructured/nested API data into a clean, structured format
- Data analysis - using pandas to organize and export tabular data
- Data visualization - building a readable, styled chart with a color scale legend
- Secure credential handling - API key stored in a local .env file (excluded from version control via .gitignore), loaded with python-dotenv
=======
1. Calls the [OpenWeatherMap API](https://openweathermap.org/api) to fetch current weather data for multiple cities
2. Parses the raw (nested, unstructured) JSON response and extracts the relevant fields
3. Loads the cleaned data into a **pandas** DataFrame and exports it to a structured CSV
4. Generates a color-coded bar chart comparing temperatures across cities using **matplotlib**

## Skills demonstrated

- **API integration** — authenticated requests, query parameters, handling JSON responses
- **Data cleaning** — converting unstructured/nested API data into a clean, structured format
- **Data analysis** — using pandas to organize and export tabular data
- **Data visualization** — building a readable, styled chart with a color scale legend
- **Secure credential handling** — API key stored in a local `.env` file (excluded from version control via `.gitignore`), loaded with `python-dotenv`
>>>>>>> 45dc94d3273a9c0c276e9474cdb61d7c84e8bd0a

## Tech stack

- Python
<<<<<<< HEAD
- requests - API calls
- pandas - data cleaning and structuring
- matplotlib - data visualization
- python-dotenv - environment variable / secret management
=======
- `requests` — API calls
- `pandas` — data cleaning and structuring
- `matplotlib` — data visualization
- `python-dotenv` — environment variable / secret management
>>>>>>> 45dc94d3273a9c0c276e9474cdb61d7c84e8bd0a

## How to run it

1. Clone this repo
2. Install dependencies: pip install requests pandas matplotlib python-dotenv
<<<<<<< HEAD
3. Get a free API key from OpenWeatherMap
4. Create a .env file in the project folder with: OPENWEATHER_API_KEY=your_key_here
5. Open Untitled2.ipynb in Jupyter and run all cells

## Output

- weather_data.csv - structured weather data for multiple cities
- temperature_chart.png - bar chart comparing city temperatures, color-scaled by temperature
=======
3. 3. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
4. Create a `.env` file in the project folder with: OPENWEATHER_API_KEY=your_key_here
5.  Open `Untitled2.ipynb` in Jupyter and run all cells

## Output

- `weather_data.csv` — structured weather data for multiple cities
- `temperature_chart.png` — bar chart comparing city temperatures, color-scaled by temperature
>>>>>>> 45dc94d3273a9c0c276e9474cdb61d7c84e8bd0a

## Next steps

Planned additions: pulling multi-day forecast data instead of a single snapshot, and automating the script to run on a schedule.
