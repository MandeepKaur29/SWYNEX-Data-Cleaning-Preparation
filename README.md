
# SWYNEX Data Cleaning & Preparation

## Dataset
Netflix Movies and TV Shows (Kaggle). X rows, 12 columns.

## Issues Found
- 2634 missing values in director,825 missing values in cast,831 missing in country
- 0 duplicate rows
- date_added stored as text
- Extra spaces and inconsistent text

## Cleaning Steps
1. Removed duplicates
2. Filled missing text values with "Unknown"
3. Removed rows with missing date_added, rating or duration
4. Converted date_added to date format
5. Standardized text using TRIM

## Result
Rows: before -> after. Missing values: before -> 0.

## Tool
Microsoft Excel
