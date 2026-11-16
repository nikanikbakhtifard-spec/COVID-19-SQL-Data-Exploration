# COVID-19 Data Exploration Using SQL

## Project Overview

This project explores COVID-19 data to analyze infection rates, mortality trends, population statistics, and vaccination patterns across countries and continents.

Using SQL, I examined two datasets, **CovidDeaths** and **CovidVaccinations**, to extract meaningful information, calculate key indicators, and explore geographic and temporal differences in reported COVID-19 statistics.

The objective was to strengthen practical SQL skills and demonstrate how structured data can be transformed into useful analytical insights.

## Datasets

The analysis uses two datasets:

- **CovidDeaths.xlsx:** Contains reported COVID-19 cases, deaths, population figures, and geographic information.
- **CovidVaccinations.xlsx:** Contains vaccination records, testing statistics, and related public-health indicators.

Both datasets contain 85,171 records and can be joined using location and date.

## Tools & Technologies

- **Language:** SQL
- **Database:** SQL Server syntax; also practiced using MySQL Workbench
- **Data Sources:** Excel (.xlsx)
- **Techniques:** Data Exploration, Aggregation, Joins, CTEs, Window Functions, Temporary Tables, Views, and Data Type Conversion

## Key Analyses

### 1. Infection and Mortality Analysis
- Calculated reported deaths as a percentage of confirmed cases.
- Compared cumulative infection counts with population sizes.
- Identified locations with the highest reported infection rates and death counts.

### 2. Geographic and Global Analysis
- Analyzed COVID-19 statistics by country and continent.
- Calculated aggregated global case and death indicators.
- Ranked locations based on infection and mortality measures.

### 3. Vaccination Analysis
- Joined deaths and vaccination datasets using location and date.
- Applied SQL window functions to calculate cumulative vaccination counts.
- Used CTEs and temporary tables to organize vaccination-related calculations.
- Created a SQL view for potential future visualizations.

## SQL Skills Demonstrated

| SQL Technique | Purpose |
|---|---|
| SELECT, WHERE | Data selection and filtering |
| GROUP BY, ORDER BY | Grouping and sorting results |
| SUM(), MAX() | Aggregate calculations |
| JOIN | Combining datasets |
| CAST(), CONVERT() | Data type conversion |
| Window Functions | Cumulative calculations |
| CTEs | Structuring complex queries |
| Temporary Tables | Storing intermediate results |
| Views | Reusable analytical queries |

## Key Takeaways

Through this project, I practiced:

- Exploring real-world datasets using SQL.
- Calculating infection, mortality, and population-based indicators.
- Comparing data across countries and continents.
- Combining multiple datasets through SQL joins.
- Applying advanced SQL techniques to organize and analyze data.

**Note:** Reported cases may include reinfections, and cumulative vaccination doses do not necessarily represent uniquely vaccinated individuals.

## Project Files

- `COVID Portfolio Project - Data Exploration.sql`
- `CovidDeaths (2).xlsx`
- `CovidVaccinations.xlsx`
