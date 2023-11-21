# Home Sales SparkSQL Analysis

## Overview

This project involves SparkSQL analysis on home sales data. The tasks include creating temporary views, partitioning data, caching, uncaching, and verifying tables.

## Repository Contents

- **Home_Sales.ipynb**: Google Colab notebook containing PySpark code for the analysis.
- **home_sales_revised.csv**: Dataset file containing home sales data.
- **README.md**: Documentation providing an overview of the project.

## Project Highlights

- Created a Spark DataFrame from the provided dataset.
- Established a temporary table named "home_sales" using SparkSQL.
- Answered specific questions using SparkSQL queries.
- Cached and uncached the "home_sales" table, comparing runtimes.
- Partitioned the data by the "date_built" field and worked with formatted Parquet data.
- Ensured uncaching of the "home_sales" temporary table.

## Repository Structure

```bash
├── Home_Sales.ipynb
└── README.md
