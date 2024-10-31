
# Report on Exploratory Data Analysis, Data Processing, and SQL Integration for AI Applications

This repository contains the code and analysis for a Python-based data exploration and manipulation assessment. The assessment includes five key questions on data analysis, exploratory data analysis (EDA), and SQL integration, showcasing essential Python libraries, data manipulation techniques, and analytical approaches in data science and artificial intelligence (AI).

## Table of Contents
- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Questions Summary](#questions-summary)
  - [Q1: Data Categorization Function](#q1-data-categorization-function)
  - [Q2: Data Concatenation and Correlation](#q2-data-concatenation-and-correlation)
  - [Q3: Windowed Mean and Statistical Calculation](#q3-windowed-mean-and-statistical-calculation)
  - [Q4: SQL Database Connection and Table Manipulation](#q4-sql-database-connection-and-table-manipulation)
  - [Q5: Exploratory Data Analysis (EDA) on Iris Dataset](#q5-exploratory-data-analysis-eda-on-iris-dataset)
- [Running the Code](#running-the-code)
- [References](#references)

### Project Overview
This project is a comprehensive assessment of skills in Python programming, NumPy, pandas, MySQL integration, and data visualization techniques. Each question is solved in an `.ipynb` notebook and can be executed in Jupyter Notebook to explore data categorization, manipulation, statistical calculations, and exploratory data analysis (EDA).

### Prerequisites
Ensure you have the following libraries installed:
- Python 3.x
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `mysql-connector-python`, `matplotlib`, `seaborn`, `scikit-learn`

To install any missing packages, use:
```bash
pip install numpy pandas mysql-connector-python matplotlib seaborn scikit-learn
```

### Questions Summary

#### Q1: Data Categorization Function
This task involves creating a function to categorize columns into numeric and categorical types without pandas' built-in methods. The function accepts a DataFrame and returns two lists: numeric and categorical columns, which aids in feature engineering for AI models.

#### Q2: Data Concatenation and Correlation
This question involves merging two datasets, removing duplicates, and displaying the shape of the final DataFrame. We also compute a correlation matrix using NumPy, identifying the two columns with the highest correlation. This task emphasizes data integration and correlation analysis for feature selection in machine learning.

#### Q3: Windowed Mean and Statistical Calculation
A NumPy array of 1000 random elements is generated, followed by calculating the mean for every 5-element window and identifying key statistical values. This step helps detect outliers and normalize data, enhancing model robustness.

#### Q4: SQL Database Connection and Table Manipulation
This task covers connecting to a MySQL database, creating tables, inserting data, and retrieving records with SQL clauses in Python. It highlights the importance of RDBMS in structured storage and efficient data preprocessing in AI.

#### Q5: Exploratory Data Analysis (EDA) on Iris Dataset
Using pandas and visualization libraries, we perform a full EDA on the Iris dataset, including descriptive statistics, visualizations, and correlation analysis. EDA is a foundational step in AI, enabling data understanding that informs model choice and feature engineering.

### Running the Code
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Robert-Jonjic/PfAI-CA1-Robert-Jonjic.git
   cd PfAI-CA1-Robert-Jonjic
   ```

2. **Open the Notebook in Jupyter**:
   ```bash
   jupyter notebook CA1_Programming_AI_Concepts.ipynb
   ```

3. **Execute each cell sequentially** to view outputs, visualizations, and analysis. Screenshots and appendices are included for reference.
