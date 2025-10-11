🔹Overview

This project performs exploratory data analysis (EDA) on the Census 2011 dataset using Python and Pandas. The goal is to extract meaningful insights about population distribution, workforce, and regional data across different Indian states and districts. It also demonstrates advanced Pandas DataFrame styling and manipulation techniques.

🔹Dataset

Dataset Name: Census+2011.csv

🔹Key Columns:

1. District_code — Unique code for each district
2. District_name — Name of the district
3. State_name — Name of the state
4. Population — Total population of the district
5. Male_Workers — Number of male workers in the district
6. Female_Workers — Number of female workers
7. Literates — Number of literate people
8. Illiterates — Number of illiterate people

🔹Tools & Libraries Used

Python 3
Pandas — Data analysis and manipulation
Jupyter Notebook — Code execution and visualization

🔹Data Analysis Performed

1. Data Loading & Inspection
=>Loaded the dataset using pandas.read_csv().
=>Displayed initial records using head().

2. Styling and Formatting
=>Hide indexes of the DataFrame using df.style.hide(axis='index').
=>Add a caption to the DataFrame using df.style.set_caption().

3. Filtering
=>Extracted records for specific districts: New Delhi, Lucknow, and Jaipur using isin().

4. Aggregations
=> Calculated total population across India using df.Population.sum().
=>Computed state-wise population using groupby('State_name').Population.sum().

5.State-Level Insights
=>Found the total number of male workers in Maharashtra.

6. DataFrame Operations
=>Set District_code as the index of the DataFrame using set_index().
=>Added prefixes and suffixes to column names using add_prefix() and add_suffix().

🔹Key Insights

1. State-wise population distribution highlights demographic variations.
2. Maharashtra has a high number of male workers compared to other states.
3. The notebook demonstrates multiple Pandas styling techniques for professional presentation.
4. Data filtering enables focused analysis of specific districts or regions.

🔹Concepts Demonstrated

1. Data selection and filtering (isin(), conditional indexing)
2. Aggregation using groupby()
3. DataFrame styling (set_caption, hide)
4. Index setting and column renaming (set_index, add_prefix, add_suffix)
5. Basic exploratory analysis

🔹How to Run This Project

1. Clone or download this repository.
2. Place Census+2011.csv in the same directory as the notebook.
3. Open the notebook in Jupyter Notebook or VS Code.
4. Run all cells sequentially to reproduce the results.

🔹Future Enhancements

1. Add visualizations for state-wise population using Matplotlib or Seaborn.
2. Explore correlations between literacy rate and workforce participation.
3. Create an interactive Tableau or Power BI dashboard for regional insights.

👨‍💻 Author

Saurabh Dwivedi
Data Science Enthusiast | Python | SQL | Pandas | Data Visualization
