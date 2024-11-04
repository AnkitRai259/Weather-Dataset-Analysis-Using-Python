# Weather-Dataset-Analysis-Using-Python


## Overview
This project performs exploratory data analysis (EDA) on a weather dataset. The dataset contains columns for various weather-related metrics, such as temperature, humidity, wind speed, pressure, visibility, and weather conditions, with timestamps for each observation. The analysis aims to uncover trends, correlations, and patterns in weather data over time.

## Datasets
The dataset is expected to contain the following columns:

* Date/Time       : The date and time of each weather observation (needs to be converted to datetime format).
* Temp_C          : Temperature in Celsius.
* Rel Hum_%       : Relative humidity as a percentage.
* Press_kPa       : Atmospheric pressure in hPa.
* Wind Speed_km/h : Wind speed in km/h.
* Weather         : Description of the weather (e.g., sunny, cloudy, rainy).
* Visibility_km   : Visibility in kilometers.
* Dew Point Temp_C: Dew point temperature in Celsius.


## Libraries Used
This project utilizes the following libraries:

Pandas: For data manipulation and analysis

Matplotlib: For creating static, interactive, and animated visualizations

Seaborn: For statistical data visualization and enhanced graphics


## Project Structure
The project is organized as follows:

Weather-Dataset-Analysis-Using-Python/

│

├── Weather Data Analysis.ipynb # Jupyter Notebook containing the analysis

├── Weather Dataset.csv # Diwali sales dataset

└── README.md # Project README file



#  Data Analysis Process

## 1.Data Loading and Preprocessing:

* The dataset is loaded, and the Date/Time column is converted to datetime format to allow for time-based grouping.

  
## 2.Daily Analysis:

* Calculate the daily average temperature and humidity to understand day-to-day variations.


## 3.Descriptive Statistics:

* Summarize temperature, humidity, wind speed, and pressure with mean, median, min, and max values.


## 4.Trend Analysis:

* Analyze monthly and seasonal trends in temperature, humidity, and visibility.


## 5.Correlation Analysis:

* Generate a heatmap to visualize correlations between weather variables like temperature, humidity, pressure, and wind speed.


## 6.Extreme Weather Analysis:

* Identify dates with extreme temperature or wind speed, helping to spot unusual weather events.  

