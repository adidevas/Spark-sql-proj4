# Spark-sql-proj4
This project performs large-scale data processing and analytical queries on global city temperature data using PySpark. The objective is to simulate database-style transformations and aggregations on structured datasets and generate query-based outputs similar to SQL operations.

In this project, you will use Apache Spark to solve the following questions using Spark SQL /
Spark DataFrame API.
Please use Google Colab to run the problems. It is a free, cloud-based platform that allows you to
write and execute Python code directly in your browser without any setup.
For this project, you will use the following input files.
i. city_temperature.csv: contains the day level average temperature values of major cities.
The file includes 8 columns: Region, Country, State, City, Month, Day, Year, and
AvgTemperature.
ii. country-list.csv: contains the capital names for each country. The file includes 3 columns:
country, capital, and type.
Q1. Your Spark implementation should compute the following: (100 Points)
A. B. Find the average of AvgTemperature for each Region. (15 Points)
Find the average of AvgTemperature by Year for countries only located in the “Africa”
Region. (15 Points)
C. Find the average of AvgTemperature by City only located in the Country “Jordan”. (15
Points)
D. For each country, find the capital and average of AvgTemperature of that capital city. (15
Points)
Your output should show:
<Capital City><TAB><Country><TAB><Avg of AvgTemperature of the Capital only>
For example, Paris is the capital of France. Therefore, when you calculate the average of
AvgTemperature for France, only consider the AvgTemperature values of the city Paris.
E. Solve the question 1D using a broadcast variable. (20 Points)
F. Solve the question 1D. While solving this question, please utilize the User Defined
Function (UDF) to do the following tasks: (20 Points)
i. ii. Use a UDF to filter the years so that Year >= 2012
Use a UDF to display your final output for each row as follows:
<Capital> is the capital of <Country> and its average temperature is <Avg of
AvgTemperature>

