# Data Science Assignment: Python Data Analysis

## Overview
This repository contains solutions to a Python-based data science assignment involving three datasets: sales records, IMDB movie ratings, and diamond characteristics. The tasks cover data manipulation, aggregation, cleaning, and analysis using `pandas` and other Python libraries.

## Datasets Used
1. **SalesData.xlsx**: Transactional sales data with columns like `OrderDate`, `Region`, `Manager`, `SalesMan`, `Item`, and `Sale_amt`.
2. **imdb.csv**: Movie metadata including `title`, `imdbRating`, `duration`, `year`, and genres.
3. **diamonds.csv**: Diamond attributes such as `carat`, `cut`, `color`, `clarity`, and physical dimensions.

## Solutions Implemented

### Sales Data Analysis (Q1-Q6)
- Calculated least sales per item and yearly/regional sales totals.
- Computed day differences from a reference date.
- Created manager-salesman mappings and regional sales summaries.
- Derived sales percentage contributions by manager.

### IMDB Data Analysis (Q7-Q10)
- Extracted ratings for specific movies.
- Identified movies with shortest/longest runtimes.
- Sorted movies by release year and rating.
- Filtered movies by duration (30-180 minutes).

### Diamonds Data Analysis (Q11-Q15)
- Counted duplicate rows and handled missing values.
- Subset numeric columns and computed conditional volume.
- Imputed missing prices with mean values.

## Code Features
- **Efficient Aggregations**: Used `groupby`, `agg`, and `pivot` operations.
- **Robust Cleaning**: Handled duplicates, missing values, and type conversions.
- **Conditional Logic**: Applied `numpy.where`/`apply` for custom calculations (e.g., diamond volume).

## Dependencies 
Python 3.8+
pandas
numpy
openpyxl (for Excel , additional support other than Pandas)
