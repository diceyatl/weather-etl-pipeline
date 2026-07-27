# 🌦️ Weather ETL Pipeline using OpenWeather API

## Project Overview

This project demonstrates the implementation of an ETL (Extract, Transform, Load) pipeline using Python and the OpenWeather API. The pipeline retrieves real-time weather data for selected Nigerian cities, transforms the raw data into a clean and structured format using Pandas, and stores the processed data for future analysis.

---

## Objective

To build a simple ETL pipeline that automates the process of collecting, cleaning, and storing weather data.

---

## Data Source

OpenWeather API

https://openweathermap.org/api

---

## Tools Used

- Python
- Jupyter Notebook
- Requests
- Pandas
- Matplotlib
- SQLite
- OpenWeather API

---

## ETL Process

### 1. Extract

Weather data was retrieved from the OpenWeather API for:

- Lagos
- Abuja
- Port Harcourt

The following information was collected:

- City Name
- Temperature
- Humidity
- Weather Condition
- Wind Speed
- Date and Time

---

### 2. Transform

The extracted data was cleaned and prepared by:

- Organizing data into a Pandas DataFrame
- Formatting timestamps
- Checking data types
- Verifying missing values
- Sorting records
- Creating a Humidity Level feature

---

### 3. Load

The processed dataset was stored as:

- weather_data.csv
- weather_data.xlsx
- weather.db (SQLite)

---

## Analysis Performed

The project compares:

- Temperature across cities
- Humidity levels
- Wind speeds
- Weather conditions

Visualizations were created to support the analysis.

---

## Key Findings

- Temperature varied across the selected cities.
- Humidity levels differed between locations.
- Wind speed was highest in one of the selected cities.
- Weather conditions were successfully compared using visualizations.

---

## Project Structure

```
AnalystLab Week 7
│
├── weather_etl.ipynb
├── weather_data.csv
├── weather_data.xlsx
├── weather.db
├── README.md
└── requirements.txt
```

---

## Author

Richard Opaleye

AnalystLab Africa Data Analytics Internship (Batch B)