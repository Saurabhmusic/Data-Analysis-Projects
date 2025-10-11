📘 Overview

This project performs exploratory data analysis (EDA) on the Census 2011 dataset using Python and Pandas. The goal is to extract meaningful insights about population distribution, workforce, and regional data across different Indian states and districts. It also demonstrates advanced Pandas DataFrame styling and manipulation techniques.

📊 Dataset

Dataset Name: Census+2011.csv

Key Columns:

District_code — Unique code for each district

District_name — Name of the district

State_name — Name of the state

Population — Total population of the district

Male_Workers — Number of male workers in the district

Female_Workers — Number of female workers

Literates — Number of literate people

Illiterates — Number of illiterate people

(Columns may vary slightly based on dataset structure.)

⚙️ Tools & Libraries Used

Python 3

Pandas — Data analysis and manipulation

Jupyter Notebook — Code execution and visualization

🔍 Data Analysis Performed

Data Loading & Inspection

Loaded the dataset using pandas.read_csv().

Displayed initial records using head().

Styling and Formatting

Hide indexes of the DataFrame using df.style.hide(axis='index').

Add a caption to the DataFrame using df.style.set_caption().

Filtering

Extracted records for specific districts: New Delhi, Lucknow, and Jaipur using isin().

Aggregations

Calculated total population across India using df.Population.sum().

Computed state-wise population using groupby('State_name').Population.sum().

State-Level Insights

Found the total number of male workers in Maharashtra.

DataFrame Operations

Set District_code as the index of the DataFrame using set_index().

Added prefixes and suffixes to column names using add_prefix() and add_suffix().

📈 Key Insights

State-wise population distribution highlights demographic variations.

Maharashtra has a high number of male workers compared to other states.

The notebook demonstrates multiple Pandas styling techniques for professional presentation.

Data filtering enables focused analysis of specific districts or regions.
