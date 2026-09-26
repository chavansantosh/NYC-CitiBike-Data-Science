# 🚲 NYC CitiBike Data Science

## 📌 Project Overview

This project analyzes **NYC Citi Bike trip data** to understand riding patterns, rider behavior, trip characteristics, and the relationship between trip duration and factors such as distance, time, and weather.

The project also applies **Linear Regression** to predict trip duration using selected trip and weather-related features.

---

## 🎯 Objectives

* Clean and prepare large-scale Citi Bike trip data
* Analyze rider and bike usage patterns
* Explore trip duration and trip distance
* Analyze trips by hour and day of the week
* Compare member and casual riders
* Study weekday vs weekend riding patterns
* Analyze the relationship between weather and trip activity
* Engineer useful features for machine learning
* Build a Linear Regression model to predict trip duration
* Evaluate model performance using regression metrics

---

## 📊 Dataset

The project uses NYC Citi Bike trip data from **July–August 2026**.

### Data sources

* Citi Bike trip data
* NYC weather data from Open-Meteo
* Citi Bike station information

The raw and processed CSV files are intentionally excluded from this repository using `.gitignore`.

---

## 🗂️ Project Structure

```text
NYC-CitiBike-Data-Science/
│
├── data/
│   ├── raw/
│   │   ├── Citi Bike CSV files
│   │   ├── nyc_weather.csv
│   │   └── station_information.csv
│   │
│   └── processed/
│       ├── citibike_trips_merged.csv
│       └── citibike_final_cleaned.csv
│
├── reports/
│   ├── bike_type_distribution.png
│   ├── distance_vs_duration.png
│   ├── linear_regression_actual_vs_predicted.png
│   ├── linear_regression_residuals.png
│   ├── precipitation_vs_trips.png
│   ├── rider_type_distribution.png
│   ├── top_10_start_stations.png
│   ├── trip_distance_distribution.png
│   ├── trip_duration_by_rider_type.png
│   ├── trip_duration_distribution.png
│   ├── trips_by_day_of_week.png
│   ├── trips_by_hour.png
│   └── weekday_vs_week
```
