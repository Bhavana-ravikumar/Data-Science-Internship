# Data Science Internship Projects 

A collection of four data science tasks completed during my Data Science internship at SkillCraft Technology. Each task covers a different part of the workflow: data cleaning, exploratory data analysis (EDA), visualization, and a machine learning model.

## Projects at a Glance

| Task | Project | Focus | Notebook |
|------|---------|-------|----------|
| 1 | India Population Distribution & Growth | Time-series analysis and visualization | `TASK_1.ipynb` |
| 2 | Heart Disease Patient Data Analysis | Data cleaning and EDA | `TASK_2.ipynb` |
| 3 | Flight Fare Classification | Decision Tree Classifier | `TASK_3.ipynb` |
| 4 | Indian Liver Patient Data Analysis | EDA and correlation analysis | `TASK_4.ipynb` |


## Task 1: India Population Distribution & Growth
- Extracted India's total population (1960 to 2024) from a country-indicator dataset and reshaped it for analysis
- Calculated year-on-year growth rates and grouped years into Low, Medium and High growth categories
- Visualized the trends with bar, line, pie and area charts, including the top 10 growth years, decade averages, cumulative growth and annotated population milestones

## Task 2: Heart Disease Patient Data Analysis
- Cleaned the data: checked missing values, removed duplicates, trimmed text fields and converted low-cardinality columns to categorical types
- Engineered an `age_group` feature and summarized the numeric indicators by age group and sex
- Explored relationships between cardiac risk indicators with visualizations and correlation analysis

## Task 3: Flight Fare Classification
- Worked with Indian flight booking records (airline, route, stops, duration, journey date, price)
- Handled missing values, extracted day and month from journey dates, converted durations to minutes and one-hot encoded the categorical features
- Framed the problem as classification by labelling each fare as Affordable or Expensive relative to the median price
- Trained a **Decision Tree Classifier** (entropy criterion, max depth 5) and evaluated it with accuracy and a classification report
- Visualized average price by airline, number of stops and route

## Task 4: Indian Liver Patient Data Analysis
- Cleaned the dataset (imputed missing Albumin/Globulin ratio values with the median)
- Univariate analysis: age, gender, bilirubin, albumin and enzyme (ALT, AST) distributions
- Bivariate and multivariate analysis: gender vs disease status, age vs bilirubin, ALT vs AST, correlation heatmap and pair plots

## Tools & Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## Datasets
The datasets were collected from various public sources and are **not included in this repository** because of their size and because they come from different providers. Each notebook loads its dataset by filename (for example `Flight_Fare.csv`), so to run a notebook, place your copy of the dataset in the same folder as the notebook.

## How to Run
1. Clone or download this repository
2. Install the dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
3. Add the dataset for the task you want to run into the same folder as its notebook
4. Open the notebook in Jupyter or Google Colab and run all cells

## About
Completed by **Bhavana R** as part of the Data Science internship at SkillCraft Technology.
