# SWYNEX-Interactive-Dashboard

Interactive Dashboard project completed as part of my Data Analyst Internship at SWYNEX Technologies.

# Task 3 – Interactive Dashboard

## Project Overview

This project was completed as part of my Data Analyst Internship at SWYNEX Technologies. The objective of this task was to create an interactive dashboard using the cleaned and analyzed Air Quality Index (AQI) dataset from Task 1 and Task 2.

The dashboard was created using Microsoft Power BI to visualize important AQI metrics, trends, city-wise comparisons, pollutant levels, and AQI category distribution.

## Dataset

The dataset used for this task is the cleaned India AQI dataset prepared during Task 1 and used for Exploratory Data Analysis in Task 2.

The cleaned dataset contains:

- **100 rows**
- **10 columns**
- Air quality information from different cities in India
- Pollutant measurements
- AQI values
- AQI categories

The main columns include:

- City
- Date
- PM2.5
- PM10
- NO2
- SO2
- CO
- O3
- AQI
- AQI_Bucket

## Tools Used

- Microsoft Power BI
- Power Query
- CSV
- VS Code

## Files
```text
SWYNEX-Interactive-Dashboard
│
├── AQI_Analysis_Dashboard.pbix
├── india_aqi_cleaned.csv
├── dashboard_screenshot.png
└── README.md
```
Dashboard Development Steps:
1. Import the Dataset
Imported the cleaned India AQI dataset into Microsoft Power BI.
2. Data Preparation
Checked the dataset in Power Query and verified the required columns and data types.
3. Create KPI Cards
Created KPI cards to display important AQI metrics:
- Average AQI
- Maximum AQI
- Average PM2.5
- Severe AQI Records
4. Create Visualizations
Created different visualizations to understand and communicate the AQI data.
The dashboard includes:
- AQI Trend Over Time
- AQI Category Distribution
- Average PM2.5 vs PM10 by City
- Average AQI by City
5. Add Interactive Filters
Added interactive filters to allow users to explore the dashboard.
The filters include:
- City
- AQI Category
- Date Range
Dashboard
The dashboard was created with the title:
INDIA AIR QUALITY ANALYSIS
The dashboard provides an interactive view of air quality across different cities in India during 2023.
 
Key Insights
Based on the analysis:
1. Hyderabad has the highest average AQI in this dataset, while Jaipur has the lowest average AQI.
2. The Severe AQI category contains the highest number of records, with 45 out of 100 records.
3. PM2.5 has the strongest positive correlation with AQI among the pollutant columns in this dataset.
4. The correlation between PM2.5 and AQI is approximately 0.89, showing a strong positive relationship in this dataset.
5. No AQI values were identified as anomalies using the mean ± 2 standard deviations method.

Conclusion
The interactive Power BI dashboard provides a clear visual representation of the India AQI dataset.
The dashboard allows users to analyze AQI trends, compare air quality across cities, understand AQI category distribution, and explore pollutant levels using interactive filters.

Learning Outcome
Through this task, I practiced creating interactive dashboards using Microsoft Power BI.
I learned how to create KPI cards, build different visualizations, add interactive filters, analyze trends and comparisons, and present data insights through an interactive dashboard.
