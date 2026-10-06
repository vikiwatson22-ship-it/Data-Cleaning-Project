# Data Cleaning Project

## Objective

The objective of this project is to clean a raw customer dataset by identifying and correcting common data quality problems.

## Dataset

The dataset contains customer information such as:

* Customer ID
* Name
* Gender
* Age
* City
* Salary
* Join Date

## Data Cleaning Performed

The following data quality issues were identified and handled:

1. **Missing Values**

   * Identified missing values in relevant columns.
   * Applied appropriate methods to handle missing data.

2. **Duplicate Records**

   * Identified duplicate customer records.
   * Removed duplicate rows.

3. **Incorrect Data Types**

   * Converted Age and Salary into appropriate numeric data types.
   * Converted Join Date into a proper date format.

4. **Inconsistent Values**

   * Standardized Gender values such as `Male`, `male`, `M`, and `MALE`.
   * Standardized city names and removed unnecessary spaces.

5. **Invalid Values**

   * Checked for invalid age values.
   * Identified invalid date values and handled them appropriately.

## Tools Used

* Python
* Pandas
* GitHub

## Files

| File                       | Description                  |
| ---------------------      | ---------------------------- |
| `data_cleaning_raw_dataset`| Original uncleaned dataset   |
| `cleaned_dataset.csv`      | Final cleaned dataset        |
| `data_cleaning.ipynb`      | Python data-cleaning process |
| `README.md`                | Project documentation        |

## Conclusion


The raw dataset was inspected, cleaned, and validated by addressing missing values, duplicate records, incorrect data types, inconsistent values, and invalid data.
