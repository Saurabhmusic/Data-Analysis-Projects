Overview

This project focuses on analyzing the spread and impact of COVID-19 across different regions using Python. The dataset includes information on confirmed cases, deaths, and recoveries, enabling insights into how the pandemic affected various parts of the world. The analysis demonstrates data cleaning, aggregation, and visualization using Pandas and Seaborn.

Dataset Name: Covid_19_data.csv

Key Columns:

ObservationDate — Date of the record

Province/State — Specific region or province (if available)

Country/Region — Country or regional name

Confirmed — Total confirmed COVID-19 cases

Deaths — Total deaths

Recovered — Total recovered cases

Tools & Libraries Used

Python 3

Pandas — Data analysis and manipulation

NumPy — Numerical computation

Matplotlib — Data visualization

Seaborn — Statistical data visualization

Data Analysis Performed

Initial Exploration

Loaded the dataset and displayed basic structure (.head(), .count()).

Checked for missing values and visualized them using a Seaborn heatmap.

Regional Analysis

Displayed total confirmed, deaths, and recovered cases by region.

Found top 10 regions with the highest confirmed cases.

Data Cleaning

Removed all records where confirmed cases < 10 to focus on meaningful data.

Statistical Insights

Identified the region with the maximum number of confirmed cases.

Found the region with the minimum number of death cases.

Extracted records for India and analyzed confirmed, deaths, and recovered cases till April 29, 2020.

Sorting

Sorted the dataset by confirmed cases (ascending order).

Sorted by recovered cases (descending order).

Key Insights

The top affected regions have significantly higher confirmed and death counts.

Data cleaning improved the focus on impactful records (confirmed ≥ 10).

Visualizing missing data helped ensure data reliability.

Sorting and grouping enabled quick comparison between regions.

India’s COVID-19 case trend was analyzed specifically to understand the local scenario up to April 2020.

Concepts Demonstrated

Data cleaning (isnull(), drop, filtering conditions)

Grouping and aggregation (groupby, sum)

Data sorting (sort_values)

Visualization of null values using Seaborn heatmap

Descriptive analysis using Pandas

How to Run This Project

Clone or download this repository.

Place Covid_19_data.csv in the same directory as the notebook.

Open the notebook in Jupyter Notebook or VS Code.

Run each cell sequentially to reproduce the analysis and plots.

📚 Future Enhancements

Add time-series visualization to show trends over time.

Create dashboards using Tableau or Power BI.

Include predictive modeling for future case trends.

👨‍💻 Author

Saurabh Dwivedi
Data Science Enthusiast | Python | Pandas | Machine Learning
