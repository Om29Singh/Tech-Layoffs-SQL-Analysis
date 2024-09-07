# Tech-Layoffs-SQL-Analysis

## Project Overview

This project conducts an Exploratory Data Analysis (EDA) on global tech industry layoffs using SQL queries. The analysis aims to uncover trends, patterns, and insights from a comprehensive dataset spanning multiple years.

## Dataset

The analysis is performed on a dataset named `world_layoffs.layoffs_staging2`, which contains information about layoffs in the tech industry. The dataset includes the following key fields:

- Company name
- Date of layoff
- Total number of employees laid off
- Percentage of workforce laid off
- Location/Country
- Industry
- Funding stage
- Funds raised (in millions)

## Key Analyses

1. **Overall Layoff Statistics**
   - Maximum and minimum percentage of workforce laid off
   - Companies that laid off 100% of their workforce

2. **Largest Layoffs**
   - Companies with the biggest single-day layoffs
   - Companies with the highest total layoffs over the entire period

3. **Geographical Analysis**
   - Layoffs by location and country

4. **Temporal Analysis**
   - Yearly layoff trends
   - Rolling total of layoffs per month

5. **Industry and Company Stage Analysis**
   - Layoffs by industry
   - Layoffs by company stage (e.g., startup, established)

6. **Top Companies with Layoffs by Year**
   - Identifies the top 3 companies with the most layoffs for each year

## SQL Techniques Used

- Basic SELECT queries with aggregations
- Subqueries
- Common Table Expressions (CTEs)
- Window functions (DENSE_RANK, SUM OVER)
- Date manipulation (YEAR, SUBSTRING)

## How to Use

1. Set up a SQL database and import the `world_layoffs.layoffs_staging2` dataset.
2. Run the SQL queries provided in the `Portfolio Project - EDA.sql` file.
3. Analyze the results to gain insights into tech industry layoff trends.

## Future Enhancements

- Visualize the results using a BI tool like Tableau or Power BI
- Incorporate additional data sources for more comprehensive analysis
- Perform predictive analysis to forecast future layoff trends


