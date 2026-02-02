
# Data Cleaning in SQL - Layoffs Dataset

## Project Overview
This project focuses on cleaning and standardizing a raw dataset containing information about company layoffs. Using **MySQL**, I transformed messy data into a structured format ready for analysis.

## Key Skills & Techniques Used
* **CTE (Common Table Expressions)**: Used for identifying and managing duplicate records.
* **Window Functions (`ROW_NUMBER`)**: Implemented to partition data and assign unique identifiers to duplicate rows.
* **Data Standardization**: Used `TRIM` to clean string data and handled inconsistent naming conventions.
* **Date Conversion**: Converted text-based dates into the proper `DATE` format using `STR_TO_DATE`.
* **Handling Nulls**: Populated missing values (e.g., industry data) using Self-Joins based on existing records.

## Podziękowania i Inspiracje
Projekt został zrealizowany w celach edukacyjnych na podstawie materiałów szkoleniowych **Alexa The Analyst**.
