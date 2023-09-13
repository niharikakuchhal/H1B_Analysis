# H1B Visa Petitions Analysis

## Overview

This repository contains an in-depth analysis of the H1B Visa Petitions dataset, which includes insights into the trends and statistics related to H1B visa applications.

### Dataset Information

- **Source**: [H1B Visa Petitions Dataset](https://link-to-your-dataset)
- **Columns**: CASE_STATUS, EMPLOYER_NAME, SOC_NAME, JOB_TITLE, FULL_TIME_POSITION, PREVAILING_WAGE, YEAR, WORKSITE, lon, lat

## Data Preparation

- Imported required libraries.
- Downloaded and loaded the dataset.
- Checked and removed unnecessary columns.

## Data Cleaning

- Checked the number of rows (3,002,458) and dropped rows with missing values.
- Displayed the first 5 rows after data cleaning.

## Data Exploration

- Reset the index after data cleaning.
- Identified the top 15 hiring companies (Employer Names) and their counts.
- Found the top 5 prevailing wages.

## Data Transformation

- Rounded latitude ('LAT') and longitude ('LON') to 2 decimal places.
- Converted 'YEAR' to a string.
- Converted 'PREV_WAGE' to an integer.
- Displayed the top 3 rows to confirm data transformation.

## Analysis of Petitions

- Analyzed unique values in 'CASE_STATUS'.
- Created a pie chart to visualize the distribution of petitions by case status.
- Created a countplot to visualize the distribution of petitions by year.
- Identified and displayed the number of denied petitions (85,161).
- Displayed the first 3 rows of denied petitions.

## Denied Petitions Analysis

- Analyzed the distribution of denied petitions by year.
- Calculated the denied petition rate by year.

## Petitions by State

- Identified unique states with sorted values.

## Analysis of Illinois State

- Checked the number of applications for the state of Illinois and how many of them were denied (2 certified).

## Top 25 Job Titles

- Identified the top 25 job titles by the number of applications.

![Top 25 Job Titles](image.png)

## Conclusion

This analysis provides valuable insights into H1B visa petitions, including trends in case status, top hiring companies, and prevalent job titles. The visualizations help in understanding the data more effectively.

Feel free to customize this README with additional details, visualizations, or any other information you find relevant for your GitHub repository.

