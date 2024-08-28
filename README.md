# Weather Data Analysis
This project analyzes historical weather data for Belgrade, Serbia over a one-year period, from August 1, 2023, to July 1, 2024. The main goals of the project are to:
+ Clean and preprocess the data.
+ Conduct basic statistical analysis (e.g., average, minimum, and maximum temperatures).
+ Identify extreme weather events (e.g., the hottest day).
+ Visualize temperature trends over time and monthly rainfall distribution.
+ Summarize key patterns and anomalies in a concise report.

## Features
+ Data Cleaning: Handles missing data, corrects inconsistencies, and converts data types for accurate analysis.
+ Statistical Analysis: Calculates average, minimum, and maximum temperatures, as well as total rainfall.
+ Extreme Weather Identification: Identifies the hottest day within the dataset.
+ Data Visualization: Includes line plots for temperature trends and bar charts for monthly rainfall distribution.

## Dataset
The dataset used in this project is `Weather_Dataset.csv` from [Visual Crossing](https://www.visualcrossing.com), which contains daily weather information for Belgrade, Serbia, including:

+ Date (datetime)
+ Temperature (temp, tempmax, tempmin, feelslike, etc.)
+ Precipitation (precip)
+ Wind, humidity, solar radiation, and other meteorological variables
## Required Libraries
To install the necessary Python libraries, run:
```
pip install pandas matplotlib numpy
```
## Download the Dataset
Place the `Weather Dataset.csv ` file in your project directory. Ensure the path is correctly referenced in the script.

## Output
+ Statistical Summary: Prints the average, minimum, and maximum temperatures, total rainfall, and the hottest day.
## Visualizations:
+ Temperature Trends: Line plot showing temperature changes over time.
+ Monthly Rainfall Distribution: Bar chart showing total rainfall per month.
