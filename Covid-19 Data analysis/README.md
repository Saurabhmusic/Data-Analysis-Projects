🔹Overview

This project focuses on analyzing the spread and impact of COVID-19 across different regions using Python. The dataset includes information on confirmed cases, deaths, and recoveries, enabling insights into how the pandemic affected various parts of the world. The analysis demonstrates data cleaning, aggregation, and visualization using Pandas and Seaborn.

🔹Dataset Name: Covid_19_data.csv

🔹Key Columns:

1. ObservationDate — Date of the record

2. Province/State — Specific region or province (if available)

3. Country/Region — Country or regional name

4. Confirmed — Total confirmed COVID-19 cases

5. Deaths — Total deaths

6. Recovered — Total recovered cases

🔹Tools & Libraries Used

Python 3

Pandas — Data analysis and manipulation

NumPy — Numerical computation

Matplotlib — Data visualization

Seaborn — Statistical data visualization

🔹Data Analysis Performed

1. Initial Exploration
=> Loaded the dataset and displayed basic structure (.head(), .count()).
=>Checked for missing values and visualized them using a Seaborn heatmap.

2. Regional Analysis

=> Displayed total confirmed, deaths, and recovered cases by region.
=> Found top 10 regions with the highest confirmed cases.

3. Data Cleaning
=>Removed all records where confirmed cases < 10 to focus on meaningful data.

4. Statistical Insights
=> Identified the region with the maximum number of confirmed cases.
=> Found the region with the minimum number of death cases.
=> Extracted records for India and analyzed confirmed, deaths, and recovered cases till April 29, 2020.

5. Sorting
=>Sorted the dataset by confirmed cases (ascending order).

Sorted by recovered cases (descending order).

🔹Key Insights

1. The top affected regions have significantly higher confirmed and death counts.
2. Data cleaning improved the focus on impactful records (confirmed ≥ 10).
3. Visualizing missing data helped ensure data reliability.
4. Sorting and grouping enabled quick comparison between regions.
5. India’s COVID-19 case trend was analyzed specifically to understand the local scenario up to April 2020.

🔹Concepts Demonstrated

1. Data cleaning (isnull(), drop, filtering conditions)
2. Grouping and aggregation (groupby, sum)
3. Data sorting (sort_values)
4. Visualization of null values using Seaborn heatmap
5. Descriptive analysis using Pandas

🔹How to Run This Project

1. Clone or download this repository.
2. Place Covid_19_data.csv in the same directory as the notebook.
3. Open the notebook in Jupyter Notebook or VS Code.
4. Run each cell sequentially to reproduce the analysis and plots.

🔹Future Enhancements

1. Add time-series visualization to show trends over time.
2. Create dashboards using Tableau or Power BI.
3.Include predictive modeling for future case trends.

👨‍💻 Author

Saurabh Dwivedi
Data Science Enthusiast | Python | Pandas | Machine Learning
