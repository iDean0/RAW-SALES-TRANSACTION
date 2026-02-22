# EXCEL DATA CLEANING

## Project Overview

This project focuses on cleaning and transforming a large, unstructured sales transactions dataset into a reliable, analysis-ready dataset using Microsoft Excel.

The raw dataset contained inconsistencies, formatting issues, missing values, and structural problems. The objective was to clean, standardize, and restructure the data to ensure accuracy and usability for reporting and analysis.

## Project Objectives

- Clean a raw sales dataset containing duplicates and inconsistent formatting  
- Fix missing values and standardize text entries  
- Convert incorrectly formatted fields into proper data types  
- Transform untidy data into a structured table ready for reporting  
- Clearly demonstrate **Before vs After** data transformation  

## Issues Identified in the Raw Dataset

The raw dataset contained:

- Inconsistent capitalization (mixed upper/lowercase text)
- Extra spaces in text fields
- Combined City–State column
- Sales amounts stored as text with ₦ symbols and commas
- Inconsistent date formats
- Missing or "not available" entries
- Potential duplicate transaction IDs

These issues reduced data reliability and prevented accurate analysis.

## Data Cleaning Process

### 1. Text Standardization
- Used `TRIM()` to remove extra spaces
- Applied `PROPER()` to standardize name and product formatting

### 2. Column Restructuring
- Split combined City–State column using **Text-to-Columns**
- Created separate City and State columns

### 3. Data Type Conversion
- Removed ₦ symbols and commas from sales values
- Converted Sales Amount column from text to numeric format

### 4. Date Standardization
- Converted all entries to proper Excel date format
- Sorted dataset by **Transaction Date (Oldest to Newest)**

### 5. Missing Values & Duplicate Checks
- Reviewed blank and inconsistent entries
- Verified uniqueness of Transaction ID to prevent duplication

## Tools & Functions Used

- TRIM  
- PROPER  
- IF  
- SUM  
- SUMIF  
- COUNTIF  
- Text-to-Columns  
- Sorting & Filtering  
- Data Formatting  

## Outcome

The raw, unstructured dataset was successfully transformed into a clean, structured, and analysis-ready dataset.

The cleaned data now supports:

- Accurate revenue computation
- Reliable performance evaluation
- Improved reporting
- Better data-driven decision-making

<img width="1910" height="695" alt="Screenshot 2026-02-22 142024" src="https://github.com/user-attachments/assets/8dd06323-560d-47a5-809c-5a13bb58ccda" />

<img width="1899" height="670" alt="Screenshot 2026-02-22 141857" src="https://github.com/user-attachments/assets/7bd1c1e8-1cf3-4efd-90b0-f26d6cd772ed" />

## Author

Daniel  
Excel Data Cleaning Project  
NGC Intelligence Hub

## Contact
📩 [Email](mailto:adeyosoye37@gmail.com)

🔗 [Linkedin](https://www.linkedin.com/in/daniel-y-/)

💬 [Chat on Whatsapp](https://wa.me/2348141512158)

