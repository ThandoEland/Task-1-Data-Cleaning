# Task 1: Data Cleaning and Preprocessing

## Overview

This project focuses on cleaning and preprocessing the **Customer Personality Analysis** dataset. The goal was to improve the quality of the data by identifying and correcting common data issues before analysis.

## Dataset

* **Dataset:** Customer Personality Analysis
* **Source:** Kaggle

## Tools Used

* Microsoft Excel

## Data Cleaning Process

The following data cleaning steps were performed:

1. Split the raw dataset into separate columns using **Text to Columns**.
2. Checked the dataset for missing values.
3. Identified **25 missing values** in the **Income** column.
4. Removed the 25 rows containing missing Income values.
5. Checked the dataset for duplicate records.
6. No duplicate records were found.
7. Reviewed text columns (`Education` and `Marital_Status`) for inconsistent spelling, capitalization, and extra spaces.
8. Verified and standardized the `Dt_Customer` date format.
9. Confirmed that numeric, text, and date columns contained the correct data types.
10. Saved the cleaned dataset as `Customer_Personality_Cleaned.xlsx`.

## Files Included

* `Customer_Personality_Original.xlsx` – Original dataset
* `Customer_Personality_Cleaned.xlsx` – Cleaned dataset
* `README.md` – Project documentation

## Outcome

The dataset was successfully cleaned and prepared for further data analysis by handling missing values, checking for duplicates, verifying data formats, and ensuring data consistency.

