# Home_Sales SparkSQL Analytics Project

## Project Overview
This project is a comprehensive exercise in utilizing Apache SparkSQL for advanced data analysis. The focus is on extracting insights from a home sales dataset, emphasizing data manipulation, query optimization, and performance benchmarking in a Spark environment. This challenge serves as a demonstration of proficiency in handling big data analytics using SparkSQL.

## Initial Setup
- **Repository Initialization**: Create a repository named `Home_Sales` on GitHub. This repository should be standalone and not linked to any existing projects.
- **Local Repository Setup**: Clone the `Home_Sales` repository to your local machine to begin development.
- **Version Control**: Ensure consistent commits and pushes to GitHub to maintain a history of changes and developments.

## Required Files
- **Module 22 Challenge Files**: Download and utilize these files as a starting point for the project.

## Project Instructions
1. **File Preparation**: Rename `Home_Sales_starter_code.ipynb` to `Home_Sales.ipynb`.
2. **Import Libraries**: Ensure all necessary PySpark SQL libraries are imported for the analysis.
3. **Data Loading**: Load the `home_sales_revised.csv` file into a Spark DataFrame.
4. **Temporary Table Creation**: Construct a temporary table named `home_sales` for data manipulation.
5. **Data Analysis Tasks**: Using SparkSQL, perform the following analysis tasks with results rounded to two decimal places:
   - Compute the average selling price of four-bedroom houses per year.
   - Determine the average selling price of homes with three bedrooms and three bathrooms, segmented by year of construction.
   - Analyze the average selling price for homes matching specific criteria (three bedrooms, three bathrooms, two floors, and a minimum of 2,000 square feet) by construction year.
   - Assess the "view" rating for homes priced at or above $350,000, including the query's runtime performance.
6. **Caching Strategy**: Implement caching for the `home_sales` temporary table.
7. **Cache Verification**: Confirm the successful caching of the table.
8. **Performance Analysis**: Execute and compare the runtime of the view rating query on both cached and uncached data.
9. **Data Partitioning**: Apply data partitioning by the "date_built" field and format the data in parquet.
10. **Parquet Temporary Table**: Establish a temporary table for the parquet-formatted data.
11. **Query Execution on Parquet Data**: Perform the view rating query on the parquet data, noting runtime and comparing it with previous executions.
12. **Table Uncaching**: Remove the `home_sales` table from cache.
13. **Cache Status Verification**: Ensure the `home_sales` table is successfully uncached.
