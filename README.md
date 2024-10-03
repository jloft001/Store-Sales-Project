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

Sales Dataset: The primary dataset used for this analysis that consisted of 5 fields and 65,533 rows, is the "store sales-data.csv (2).pdf" file, containing fields specific to the store id, department number, the week end date, the sales for the given week and if that week consisted of a holiday.

## Tools

PostGreSQL- Data Cleaning
PostGreSQL- Data Analysis
Tableau- Data Visualization

## Data Cleaning/Preparation

Although this dataset was simplistic is size, I chose to clean this data within SQL. Converting the corresponding columns that contains numeric values from 'text' to 'int' values. 

## Exploratory Data Analysis

In working to manipulate the data, one limitation faced, was being able to convert the dates to standard form for SQL. Despite utilizing resources available and input accurate codes which returned successfully, the week end date remained in its original format.

![Store query  (1)](https://github.com/user-attachments/assets/e662c731-1707-439b-a7c5-e2ead453b1c2)

## Findings/Results

Analysis results summarized as follows: 

![Store Sales Dashboard (1)](https://github.com/user-attachments/assets/018cfd51-f8f0-4384-865d-54d26e7b32cd)

This district of 7 stores, dependent on its expeditures could be a profitable district. Based on the information gathered, its best performing store is store id: 4 with an aggregated sales volume of $286M for the course of 3 years.

Stores 7, 5, and 3 seem the be the lower volume stores, resulting in negative sales impact on the district.

The data analysis result of the 'ifholiday' count according to sales determined that the sales volume is not dependent on the week consisting of a holiday. Nor did the aggregation of holiday sales surpass normal weeks of sales.

## Recommendations

Based on the analysis, I recommend the following actions:

Created a clearance sale of merchandise within the departments experiencing astronomical decreases in sales. As store #7 has only 56 departments, this could be based on location or demand for specific items. Eliminating unnecessary departments results in sustaining cash on hand rather than creating a budget for merchandise that will not bring in a profit or return on investment. 




