🔹Overview

This project performs an in-depth analysis of weather data using Python and Pandas. The goal is to explore and analyze various weather parameters such as temperature, humidity, wind speed, visibility, and atmospheric pressure to extract meaningful insights and answer specific analytical questions.

🔹Dataset

The dataset used is Project+1+-+Weather+Dataset.csv, which contains several weather-related columns such as:

1. Date/Time — Timestamp of the recorded observation
2. Temp_C — Temperature in Celsius
3. Dew Point Temp_C — Dew point temperature
4. Rel Hum_% — Relative humidity in percentage
5. Wind Speed_km/h — Wind speed in kilometers per hour
6. Visibility_km — Visibility distance in kilometers
7. Press_kPa — Atmospheric pressure in kilopascals
8. Weather — Description of weather condition

🔹Tools & Libraries Used

Python 3
Pandas — Data manipulation and analysis
NumPy — Numerical computations
Jupyter Notebook — Code execution and visualization

🔹Data Analysis Performed

1. The analysis answers multiple real-world weather-related questions:
2. Find all the unique wind speed values in the dataset.
3. Count the number of times the weather was clear.
4. Count the number of times wind speed was exactly 4 km/h.
5. Identify null values in the dataset.
6. Rename the column Weather to Weather Condition.
7. Find the mean visibility.
8. Find the standard deviation of pressure.
9. Find the variance of relative humidity.
10. List all instances when snow was recorded.
11. Find all instances when wind speed > 24 km/h and visibility = 25 km.

🔹Key Insights

1. The dataset contains diverse weather conditions such as Clear, Fog, Snow, and Rain.
2. Visibility and wind speed show significant variation across conditions.
3. Snow occurrences were effectively filtered using string-based search operations.
4. The project demonstrates use of groupby, filtering, value_counts(), and statistical methods like .mean(), .std(), and .var().

🔹Concepts Demonstrated

1. Data cleaning and inspection (.info(), .isnull(), .notnull())
2. Filtering data using conditions and string matching
3. Aggregation and grouping
4. Column renaming and data transformation
5. Descriptive statistics using Pandas

🔹How to Run This Project

1. Clone this repository or download the notebook file.
2. Place the dataset (Project+1+-+Weather+Dataset.csv) in the same directory.
3. Open the notebook using Jupyter Notebook or VS Code.
4. Run all cells sequentially to reproduce the analysis.

🔹Future Enhancements
1. Perform visualizations using Matplotlib and Seaborn.
2. Build a dashboard in Tableau or Power BI for interactive exploration.
3. Apply time-series analysis to identify seasonal patterns or trends.

👨‍💻 Author

Saurabh Dwivedi
Data Science Enthusiast | Python | SQL | Machine Learning
