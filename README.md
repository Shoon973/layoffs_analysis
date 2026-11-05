# Tech & Startup Layoffs Analysis Dashboard (2020–2026)

## Project Overview

This project analyses layoffs across technology companies and startups from March 2020 to April 2026 using Microsoft Excel.

The goal is to understand layoff trends, identify the industries and countries most affected, compare company funding stages, and explore how layoffs changed over time.

I cleaned and organised the data, created calculations, and built an interactive Excel dashboard to make the results easier to understand.

## Tools Used

- **Microsoft Excel**
- Excel formulas and functions
- Pivot-style calculations and helper tables
- Charts and data visualisation
- Data cleaning and analysis

## Dataset

The dataset contains company layoff information, including:

- Date of layoffs
- Company name
- Industry
- Country and location
- Company funding stage
- Total employees laid off
- Percentage of employees laid off
- Funds raised

The original dataset contained 4,361 records.

After cleaning, 5 duplicate records were removed, leaving **4,355 layoff records**.

## Project Steps

### 1. Data Cleaning

- Reviewed the original dataset.
- Removed 5 duplicate records.
- Converted dates into the correct date format.
- Replaced missing industry, country, and funding stage values with "Unknown".
- Standardised company names with inconsistent capitalisation.
- Created additional columns, including Year, Month, and Stage Group.

### 2. Data Analysis

Explored questions such as:

- Which companies had the highest number of layoffs?
- Which industries were affected the most?
- Which countries experienced the most layoffs?
- How did layoffs change from 2020 to 2026?
- Which company funding stages experienced the most layoffs?
- How many companies reported laying off 100% of their employees?

### 3. Dashboard Creation

Created an interactive Excel dashboard with:

- Total employees laid off
- Number of layoff events
- Number of affected companies
- Median percentage of employees laid off
- Headcount reporting coverage
- Total company shutdowns
- Charts showing layoffs by industry, country, company stage, and month

The dashboard includes dropdown filters for:

- Year
- Industry
- Country
- Stage Group

These filters allow users to explore different parts of the dataset.

## Dashboard Preview

Open the `layoffs_dashboard.xlsx` file and go to the **Dashboard** sheet to explore the interactive dashboard.

## Key Data Notes

- The dataset covers March 11, 2020, to April 20, 2026.
- The 2026 data is incomplete because it only covers part of the year.
- Approximately 35% of layoff records have missing employee counts.
- Total layoffs are therefore lower-bound estimates, not necessarily the complete number of employees affected.
- The median layoff percentage uses only records where a percentage was reported.
- The source contains only 44 events for 2021, which may indicate incomplete reporting.

## Files in This Project

| File | Description |
|---|---|
| `layoffs_dashboard.xlsx` | Excel workbook containing the cleaned data, calculations, notes, and interactive dashboard |
| `README.md` | Project documentation |

## What I Learned

Through this project, I practised:

- Cleaning and preparing real-world data.
- Working with missing values and duplicates.
- Using Excel formulas and functions.
- Creating calculated columns.
- Grouping company funding stages.
- Analysing trends and patterns.
- Building interactive dashboards.
- Communicating findings through data visualisation.

## Conclusion

This project helped me develop practical data analytics skills using Excel. It demonstrates how raw data can be cleaned, analysed, and transformed into an interactive dashboard that helps people understand real-world business problems.

# layoffs_analysis
