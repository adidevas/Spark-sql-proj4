# Spark-sql-proj4
This project performs large-scale data processing and analytical queries on global city temperature data using PySpark. The objective is to simulate database-style transformations and aggregations on structured datasets and generate query-based outputs similar to SQL operations.

Project Description – Spark SQL Temperature Data Analysis

This project implements large-scale data processing and analytical queries using PySpark on global city temperature data.

The objective is to simulate SQL-style data transformations and aggregations using Spark DataFrames while working with structured CSV datasets.

The assignment focuses on:
	•	Loading and validating structured datasets
	•	Cleaning and filtering invalid records
	•	Performing aggregation and grouping operations
	•	Generating query-based analytical outputs
	•	Exporting results into structured CSV files


The project uses two input datasets:

1. city_temperature.csv

Contains historical temperature records for cities worldwide.
Columns include:
	•	Region
	•	Country
	•	State
	•	City
	•	Month
	•	Day
	•	Year
	•	AverageTemperature

This dataset is used for all analytical queries.

⸻

2. country-list.csv

Contains country codes and corresponding country names.
Used for validating and mapping country information when necessary.

Tasks Implemented:

The project includes multiple query-based tasks, each producing a corresponding output file.

Q1A – Basic Data Filtering
	•	Remove invalid temperature records
	•	Handle missing or malformed entries
	•	Export cleaned dataset

  Q1A_output.csv

Q1B – Aggregation Operations
	•	Perform grouping and aggregation operations
	•	Compute statistical measures such as averages

  Q1B_output.csv

Q1C – Advanced Filtering
	•	Apply conditional filtering based on specific temperature or regional criteria

  Q1C_output.csv

Q1D – Grouped Analytics
	•	Perform multi-column group-by operations
	•	Aggregate results by country, region, or time period

Q1D_output.csv

Q1E – Additional Transformations
	•	Perform additional transformations and calculations
	•	Generate formatted analytical outputs

Q1E_output.csv

Q1F – Two-Part Processing

Part 1:
	•	Filter dataset according to specified constraints
	•	Export intermediate result

Q1F_part1_filtered.csv

Part 2:
	•	Format and structure final analytical results
	•	Produce finalized output

Q1F_part2_formatted.csv




  
