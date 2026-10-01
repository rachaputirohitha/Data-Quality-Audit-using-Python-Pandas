# Task 24 – Data Quality Audit using Python & Pandas

## Project Overview

This project focuses on performing a Data Quality Audit on the Sample Superstore dataset using Python and Pandas.

The objective was to identify missing values, duplicate records, invalid values, date inconsistencies, and formatting issues, and then create a cleaned version of the dataset.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Google Colab

## Dataset

Dataset: Sample - Superstore

- Rows: 9,994
- Columns: 21

## Data Quality Checks

The following checks were performed:

- Missing value analysis
- Duplicate record detection
- Order Date validation
- Ship Date validation
- Ship Date vs Order Date consistency
- Quantity validation
- Discount range validation
- Sales validation
- Postal Code format validation

## Key Findings

| Data Quality Check | Result |
|---|---:|
| Missing Values | 0 |
| Duplicate Rows | 0 |
| Invalid Order Dates | 0 |
| Invalid Ship Dates | 0 |
| Ship Date Before Order Date | 0 |
| Invalid Quantity | 0 |
| Invalid Discount | 0 |
| Invalid Sales | 0 |
| Postal Code Format Issues | 449 |

The main issue identified was Postal Code formatting. 449 records contained four-digit postal codes. These were standardized as five-character text values using zero-padding.

## Data Cleaning

The cleaned dataset was created by:

1. Creating a copy of the original dataset.
2. Converting Postal Code to text.
3. Standardizing Postal Code to five characters.
4. Validating the cleaned dataset.

No records were unnecessarily deleted.

## Project Files
- `Superstore_Cleaned.csv` – cleaned dataset
- `Task_24_Data_Quality_Audit_Report.pdf` – project report

## Conclusion

The audit showed that the dataset was generally clean, with no missing values, duplicate rows, invalid dates, invalid quantities, invalid discounts, or invalid sales values. The primary formatting issue involved Postal Codes, which was standardized during the cleaning process.

## Skills Demonstrated

Python | Pandas | Data Cleaning | Data Quality Analysis | Data Validation | Exploratory Data Analysis
