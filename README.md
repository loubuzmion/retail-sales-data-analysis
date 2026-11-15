# retail-sales-data-analysis

## Project Overview

This project explores an online retail sales dataset using Python and its data analysis libraries. The objective is to clean, manipulate, merge, and analyse sales data to identify patterns, understand sales performance, and extract meaningful business insights.

The project combines three datasets: Sales, Invoice, and Product, to perform a comprehensive exploratory data analysis (EDA).

## Project Objectives

- Load and explore multiple datasets using Pandas.
- Perform data cleaning and handle missing values.
- Calculate sales revenue using quantity and unit price.
- Merge multiple DataFrames using common identifiers.
- Analyse sales distributions and trends over time.
- Examine relationships between numerical variables.
- Summarise sales performance using grouping and pivot tables.

## Tools & Technologies

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualisation
- **Seaborn** – Statistical data visualisation
- **Jupyter Notebook** – Development environment
- **Microsoft Excel** – Source dataset

## Project Workflow

### 1. Data Loading
Imported three Excel worksheets into separate Pandas DataFrames:
- Sales
- Invoice
- Product

### 2. Data Cleaning and Preparation
- Created a Sales column using Quantity × UnitPrice.
- Checked for missing values.
- Replaced missing Sales and UnitPrice values with zero.
- Calculated descriptive statistics, including mean, median, mode, and standard deviation.

### 3. Data Integration
Merged the Sales, Invoice, and Product DataFrames using InvoiceNo and StockCode to create a combined dataset for analysis.

### 4. Exploratory Data Analysis (EDA)
- Examined missing values and zero values.
- Filtered transactions to include positive quantities.
- Explored sales distributions and potential outliers.
- Prepared monthly sales data for trend analysis.

### 5. Data Visualisation
Created visualisations to explore:
- Relationship between Quantity and Sales.
- Distribution of Sales.
- Monthly Sales Trends.
- Correlation between Quantity and Sales.

### 6. Correlation Analysis
Calculated and visualised the correlation between Quantity and Sales using a heatmap.

### 7. Grouping and Aggregation
- Grouped sales by Product Category.
- Created a pivot table to explore sales by Country and Product Category.

## Key Findings

- Quantity and Sales have a strong positive correlation of approximately **0.98**.
- Sales distribution and trends were explored using histograms, scatter plots, and line charts.
- Product category aggregation revealed differences in sales performance across categories.
- Monthly sales analysis provided an overview of sales activity over time.

## Skills Demonstrated

- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Data Manipulation
- DataFrame Merging
- Statistical Analysis
- Data Aggregation
- Data Visualisation
- Business Data Exploration

## Key Learning Outcomes

Through this project, I developed practical experience in using Python and Pandas to work with structured datasets, perform exploratory analysis, and visualise data.

This project strengthened my foundational data analytics skills and my ability to transform raw data into meaningful information.
