# Task 02 – Data Cleaning | Messy Employee Dataset

## 📌 Project Overview

This project was completed as part of my **Oasis Infobyte (OIBSIP) Data Analytics Internship**.

The objective of this task was to clean, validate, standardize, and prepare a messy employee dataset for further analysis.

The dataset contained common real-world data quality issues such as missing values, inconsistent data types, formatting problems, and values requiring standardization.

---

## 🎯 Objectives

The main objectives of this project were to:

- Inspect the dataset and identify data quality issues
- Handle missing values appropriately
- Detect and remove duplicate records
- Standardize text-based columns
- Correct inconsistent data formats
- Convert date columns into proper datetime format
- Validate numerical ranges
- Detect potential outliers
- Correct data types
- Validate the cleaned dataset
- Export the final cleaned dataset for future analysis

---

## 🗂️ Dataset

The dataset is a synthetic employee dataset containing information about employees, departments, employment status, salary, contact details, performance, and remote work status.

### Dataset Dimensions

- **Rows:** 1,020
- **Columns:** 12

### Main Columns

| Column | Description |
|---|---|
| Employee_ID | Unique employee identifier |
| First_Name | Employee first name |
| Last_Name | Employee last name |
| Age | Employee age |
| Department_Region | Department and region |
| Status | Employment status |
| Join_Date | Employee joining date |
| Salary | Employee salary |
| Email | Employee email |
| Phone | Employee phone number |
| Performance_Score | Employee performance rating |
| Remote_Work | Remote work status |

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Data Cleaning Process

### 1. Initial Data Inspection

The dataset was inspected to understand:

- Dataset shape
- Column names
- Data types
- Missing values
- Duplicate records
- Numerical ranges
- Basic data quality issues

---

### 2. Missing Value Handling

Missing values were identified in the following columns:

- `Age`
- `Salary`

Instead of deleting records, missing numerical values were handled using **median imputation**.

Median was selected because it is less affected by extreme values and helps preserve the existing records.

---

### 3. Duplicate Records

The dataset was checked for duplicate rows and duplicate employee IDs.

No duplicate full rows were found, and employee IDs were unique.

---

### 4. Data Standardization

Text and categorical fields were standardized to improve consistency.

The following cleaning steps were applied:

- Removed unnecessary leading/trailing spaces
- Standardized employee names
- Standardized categorical values
- Converted email addresses to lowercase
- Standardized Employee IDs
- Cleaned phone number formatting

---

### 5. Phone Number Cleaning

The phone column contained negative numeric representations.

The values were converted into a consistent **10-digit phone number format** by removing the negative sign and converting the values into strings.

---

### 6. Date Conversion

The `Join_Date` column was converted from text format into a proper datetime format.

This makes the column suitable for:

- Date-based analysis
- Sorting
- Filtering
- Time-based calculations

---

### 7. Range Validation

Numerical and date columns were checked for invalid values.

Validation was performed for:

- Employee age
- Salary
- Joining dates
- Employee IDs

---

### 8. Outlier Detection

The **Interquartile Range (IQR)** method was used to identify potential outliers in numerical columns.

Outlier analysis was performed on:

- `Age`
- `Salary`

No significant outliers requiring removal or capping were identified.

Therefore, no valid observations were removed.

---

### 9. Data Type Correction

Data types were reviewed and corrected where necessary.

Examples include:

- `Employee_ID` → string
- `Join_Date` → datetime
- `Phone` → string
- Numerical columns → appropriate numeric types

---

## 📊 Before vs After

### Before Cleaning

The original dataset contained:

- Missing values in Age (211) and Salary(24)
- Phone numbers requiring formatting
- Inconsistent data representations
- Columns requiring data type correction

### After Cleaning

The final dataset contains:

- **1,020 rows**
- **12 columns**
- **0 missing values**
- **0 duplicate rows**
- Standardized text fields
- Corrected data types
- Proper datetime formatting
- Validated numerical values

---

## 📸 Project Preview
**Before VS After**

<img width="957" height="701" alt="messy 1" src="https://github.com/user-attachments/assets/2c19c3e7-0e65-43d5-be93-c9047700ca70" />


<img width="962" height="697" alt="messy 2" src="https://github.com/user-attachments/assets/ab33ecfe-56ef-44e5-9bed-1bb947084fda" />


<img width="1552" height="701" alt="cleaned" src="https://github.com/user-attachments/assets/cb0811bd-ecf3-49d8-9498-969b87ba751c" />

----


## 💡 Key Learnings

Through this project, I practiced:

- Data quality assessment
- Missing value handling
- Duplicate detection
- Data standardization
- Data type correction
- Date formatting
- Outlier detection using IQR
- Data validation
- Exporting cleaned datasets

---

## ✅ Conclusion

The employee dataset was systematically cleaned, standardized, and validated to create an analysis-ready dataset.

The cleaning process included handling missing values, checking duplicates, standardizing text and identifiers, converting dates, validating numerical values, and performing outlier detection.

The final cleaned dataset can now be used for:

- Exploratory Data Analysis (EDA)
- Data visualization
- Reporting
- Excel and Power BI dashboards
- Further analytical tasks

Phone records marked **Review** should be verified against the original source before being used for contact operations.


----
## 👩‍💻 Author

**Mehwish Iqbal**

Aspiring Data Analyst

Skills: Python | SQL | Excel | Power BI | Data Analysis | Data Visualization


