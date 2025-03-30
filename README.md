# Introduction:
This repository contains a comprehensive data analysis project exploring two key datasets:

1. #### COVID-19 Vaccination & Death Trends (Global and China-specific analysis)

2. #### Chicago Crime Patterns (2018-2022) with weather correlation

The project combines SQL data mining with Python visualization to uncover insights about:

- Pandemic progression and vaccination rates

- Crime trends in Chicago neighborhoods

- Relationships between crime, weather, and temporal factors

### Key Features:

- 15+ SQL queries extracting meaningful patterns from relational databases

- Interactive matplotlib/seaborn visualizations

- Time-series analysis of health and crime data

- Geographic and demographic correlations

Built using:

- Python (pandas, matplotlib, seaborn)

- SQL Server (pyodbc)

- Quarto for reproducible reporting

Perfect for data professionals interested in public health analytics, urban crime patterns, or SQL/Python data mining techniques.

## 1. Covid Vaccine Project:
### dataset:
Covid Vaccination
### Tasks:
1. Two methods used to alter date type , but the first one cannot work successfully and the second one is to create a new date column first then refer to the transformed date column.
2. Count null values in the dataset
3. Some duplicate records have values, some do not. How to populate missing values using another duplicate record.
4. Break out address values into individual columns.
5. Use case when function to change categorical values.
6. How to remove duplicate

## 2. Chicago Crime project:
### Dataset:
Chicago_crime_weather
### Tasks:
1. Create tables and set up primary key and foreign keys. Concatenate all crime tables to create a new table. Build a schema between fact table and dimension tables.
2. Use count() function to extract criminal amount, and calculate the percentage of each type crime.
3. Find the median value of temperature which is a triky one due to no in-build median function in SQL.
4. Create Common Table Expression (CTE) to helo retrive complex figures.
5. Deal with date type data, including extract day of week, day of year, consecutive days of #crime#.
6. Find Year-to-Year growth of crime and Season-to Season growth of crime.

## 3. Link
Please find more details on the upper right side of this page by visiting the link provided in the picture attached below.

![Screenshot 2025-03-11 210146](https://github.com/user-attachments/assets/cda6a7d2-4e56-4fac-a8b4-00369ed5d500)


