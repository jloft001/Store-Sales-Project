# Store_Sales_Evaluation

## Table of Contents
[Overview](#Overview)

[Data Source](#Data_Source)

[Tools](#Tools)

[Data Cleaning Preparation](#Data_Cleaning_Preparation)

[Exploratory Data Analysis](#Exploratory_Data_Analysis)



## Overview

This repository will present a data analysis on general store sales, evaluating how a "week end" holiday triggers sales.

## Data Source

Sales Dataset: The primary dataset used for this analysis is the "store_sales_data.csv" file, containing columns pertaining to the store id, department number, the week end date, the sales for the given week and if that week consisted of a holiday.

## Tools

PostGreSQL- Data Cleaning
PostGreSQL- Data Analysis
Tableau- Data Visualization

## Data Cleaning/Preparation

Although this dataset was simplistic is size, I chose to clean this data within SQL. Converting the corresponding columns that contains numeric values from 'text' to 'int' values. 

## Exploratory Data Analysis

In working to manipulate the data, one limitation faced, was being able to convert the dates to standard form for SQL. Despite utilizing resources available and input accurate codes which returned successfully, the week end date remained in its original format.

SELECT store_id,
       department,
       week_end_date,
       weekly_sales
FROM store_sales
WHERE week_end_date BETWEEN '2010-01-01' AND '2010-12-31'
GROUP BY store_id, department, week_end_date, weekly_sales;

