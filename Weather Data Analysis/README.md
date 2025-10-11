Overview

This project performs an in-depth analysis of weather data using Python and Pandas. The goal is to explore and analyze various weather parameters such as temperature, humidity, wind speed, visibility, and atmospheric pressure to extract meaningful insights and answer specific analytical questions.

Dataset

The dataset used is Project+1+-+Weather+Dataset.csv, which contains several weather-related columns such as:

Date/Time — Timestamp of the recorded observation

Temp_C — Temperature in Celsius

Dew Point Temp_C — Dew point temperature

Rel Hum_% — Relative humidity in percentage

Wind Speed_km/h — Wind speed in kilometers per hour

Visibility_km — Visibility distance in kilometers

Press_kPa — Atmospheric pressure in kilopascals

Weather — Description of weather condition

Tools & Libraries Used

Python 3

Pandas — Data manipulation and analysis

NumPy — Numerical computations

Jupyter Notebook — Code execution and visualization

Data Analysis Performed

The analysis answers multiple real-world weather-related questions:

Find all the unique wind speed values in the dataset.

Count the number of times the weather was clear.

Count the number of times wind speed was exactly 4 km/h.

Identify null values in the dataset.

Rename the column Weather to Weather Condition.

Find the mean visibility.

Find the standard deviation of pressure.

Find the variance of relative humidity.

List all instances when snow was recorded.

Find all instances when wind speed > 24 km/h and visibility = 25 km.

Key Insights

The dataset contains diverse weather conditions such as Clear, Fog, Snow, and Rain.

Visibility and wind speed show significant variation across conditions.

Snow occurrences were effectively filtered using string-based search operations.

The project demonstrates use of groupby, filtering, value_counts(), and statistical methods like .mean(), .std(), and .var().

Concepts Demonstrated

Data cleaning and inspection (.info(), .isnull(), .notnull())

Filtering data using conditions and string matching

Aggregation and grouping

Column renaming and data transformation

Descriptive statistics using Pandas

How to Run This Project

Clone this repository or download the notebook file.

Place the dataset (Project+1+-+Weather+Dataset.csv) in the same directory.

Open the notebook using Jupyter Notebook or VS Code.

Run all cells sequentially to reproduce the analysis.

Future Enhancements

Perform visualizations using Matplotlib and Seaborn.

Build a dashboard in Tableau or Power BI for interactive exploration.

Apply time-series analysis to identify seasonal patterns or trends.

👨‍💻 Author

Saurabh Dwivedi
Data Science Enthusiast | Python | SQL | Machine Learning
