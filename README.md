# Amazon ML Challenge 2026 — Entity Resolution
## Data Cleaning

The data cleaning process prepares the source datasets for analysis and entity resolution. It helps improve data consistency and makes the records easier to work with in the next stages.

## Post-Cleaning Exploratory Data Analysis (EDA)

**Notebook:** [Post_Cleaning_EDA.ipynb](Post_Cleaning_EDA.ipynb)

After cleaning the data, we performed exploratory data analysis (EDA) to understand the datasets and check their quality.

### Analysis Performed

- **Dataset Overview:** Checked the size and structure of each dataset.
- **Missing Values:** Identified missing and empty values in important fields.
- **Duplicate Analysis:** Checked for duplicate records and entity IDs.
- **Country Distribution:** Examined how records are distributed across countries.
- **Business Name Analysis:** Looked at normalized business names, repeated names, and missing name values.
- **Address Analysis:** Examined normalized addresses, repeated addresses, and missing address values.
- **Length Analysis:** Studied the lengths of business names and addresses.
- **Data Quality Checks:** Reviewed country-related data and records containing multiple addresses.

### Purpose

This analysis helps us understand the quality of the cleaned data and identify patterns that may affect entity matching. The findings will help guide the development of blocking rules and candidate pair generation for entity resolution. The performance of the matching methods will be evaluated separately using suitable ground-truth labels and evaluation metrics.
