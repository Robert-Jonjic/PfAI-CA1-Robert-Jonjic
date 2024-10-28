# Report on Exploratory Data Analysis, Data Processing, and SQL Integration for AI Applications    

This repository contains the code and analysis for a Python-based data exploration and manipulation assessment. The assessment consists of five key questions focusing on data analysis, exploratory data analysis (EDA), and SQL integration. Each question highlights essential Python libraries, data manipulation techniques, and analytical approaches applicable in data science and artificial intelligence (AI).  
  
## Table of Contents:  
Project Overview  
Prerequisites  
Questions Summary  
Q1: Data Categorization Function  
Q2: Data Concatenation and Correlation  
Q3: Windowed Mean and Statistical Calculation  
Q4: SQL Database Connection and Table Manipulation  
Q5: Exploratory Data Analysis (EDA) on Iris Dataset  
Running the Code  
References  
  
### Project Overview  
This project serves as a comprehensive assessment of skills in Python programming, NumPy, pandas, MySQL integration, and data visualization techniques. Each question is solved in an .ipynb notebook file and can be executed in a Jupyter Notebook environment to explore data categorization, manipulation, statistical calculations, and exploratory data analysis (EDA).  

### Prerequisites  
Ensure you have the following libraries installed:  

Python 3.x  
Jupyter Notebook  
Libraries: numpy, pandas, mysql-connector-python, matplotlib, seaborn, and scikit-learn  
Install any missing packages using pip:  

bash  
pip install numpy pandas mysql-connector-python matplotlib seaborn scikit-learn  

### Questions Summary  
### Q1: Data Categorization Function  
In this task, we created a user-defined function to categorize columns into numeric and categorical types without using pandas' built-in methods. The function accepts a DataFrame and returns two lists: numeric and categorical columns. This function is key for feature engineering in AI models, providing efficient data preprocessing methods.  

### Q2: Data Concatenation and Correlation  
This question involves merging two datasets from Q1 using pandas, removing duplicate rows, and displaying the shape of the final DataFrame. Additionally, we used NumPy to compute a correlation matrix, identifying the two columns with the highest correlation. This task underlines the importance of data integration and correlation analysis for feature selection in machine learning.  

### Q3: Windowed Mean and Statistical Calculation  
Here, we generated a NumPy array of 1000 random elements, calculated the mean for every 5-element window, and identified the minimum, maximum, and absolute maximum values in the dataset. Such calculations help detect outliers and normalize data, enhancing model robustness in AI applications.  

### Q4: SQL Database Connection and Table Manipulation  
In this task, we connected to a MySQL database, created tables, inserted data, and retrieved records using SQL clauses in Python. We discussed the significance of Relational Database Management Systems (RDBMS) like SQL in AI, where structured storage, efficient retrieval, and data preprocessing are critical for scaling AI systems.  

### Q5: Exploratory Data Analysis (EDA) on Iris Dataset  
This question involves a full EDA on the Iris dataset using pandas and visualization libraries. The analysis includes descriptive statistics, visualizations (histograms, boxplots), and a correlation matrix to provide insights into feature distributions and interrelationships. EDA is a foundational step in AI, enabling data understanding, which informs model choice and feature engineering.  

### Running the Code  
1. Clone the repository:  
bash  
git clone https://github.com/Robert-Jonjic/PfAI-CA1-Robert-Jonjic.git  
cd PfAI-CA1-Robert-Jonjic  

2. Open the CA1_Programming_AI_Concepts.ipynb in Jupyter Notebook:  
bash  
jupyter notebook CA1_Programming_AI_Concepts.ipynb  

3. Execute each cell in the notebook sequentially to view outputs, visualizations, and any analysis. Screenshots and appendices are included for easier reference.
