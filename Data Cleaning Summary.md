# Data Cleaning Summary

## Overview
The data cleaning process involves handling missing values, formatting data for consistency, and transforming categorical features into numerical values to prepare the dataset for further analysis.

## Key Steps

### 1. Missing Values Handling
- **Identifying Missing Data:** We checked for missing values in critical columns such as `Mileage`, `Engine`, `Power`, and `Seats`.
- **Removal of Rows with Missing Values:** Since the percentage of missing values was low (<1%), we dropped rows with missing values to ensure data quality.

### 2. Data Formatting
- **Removing Units from Values:** Columns like `Mileage`, `Engine`, and `Power` contained textual units (e.g., 'km/kg', 'bhp', 'CC') that were removed to make the data easier to convert to numerical types.
- **Converting to Numerical Types:** After removing units, the columns were converted to `float` data types for proper analysis.

### 3. Feature Engineering
- **Extracting Car Brand:** We created a new feature, `Brand`, by extracting the first word from the `Name` column, as the car brand is typically the first word in the car name.

### 4. Label Encoding
- **Transforming Categorical Features:** We converted categorical variables such as `Fuel_Type`, `Transmission`, `Location`, `Brand`, and `Owner_Type` into numerical values using label encoding to prepare them for machine learning models.

## Final Dataset
The dataset, after cleaning, now contains 5872 rows and 12 columns, ready for analysis and modeling. The columns are:

- `Name`, `Location`, `Year`, `Kilometers_Driven`, `Fuel_Type`, `Transmission`, `Owner_Type`, `Mileage`, `Engine`, `Power`, `Seats`, `Price`, `Brand`

## Tools Used

- **Pandas:** For data manipulation, checking for missing values, and performing type conversions.
- **Python String Methods:** To clean columns by removing units from values (e.g., using `str.replace()`).
- **Label Encoding:** Used to convert categorical variables into numerical values for model interpretation.


## Conclusion
The dataset has been thoroughly cleaned: missing values have been addressed, units have been removed, and categorical features have been converted to numerical values, ensuring the data is ready for further modeling.
