# Data Cleaning and Visualization Project

##### **Project Type:** Data Cleaning & Visualization
##### **Industry:** Thiranex
##### **Contribution:** Individual
##### **Project Domain:** Employee Salary Analysis

## 1. Project Overview

The **Data Cleaning and Visualization Project** focuses on cleaning, processing, and visualizing an Employee Salary Dataset using Python.

The main objective is to identify and handle data quality issues such as missing values, duplicate records, and outliers. The cleaned dataset is then used to create visualizations to understand employee information and identify meaningful insights.

The project includes data inspection, preprocessing, outlier detection and treatment, and data visualization using Python libraries.

## 2. Project Objectives

- Explore and understand the raw employee salary dataset.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Identify and handle outliers using the IQR method.
- Correct data types for accurate processing.
- Create visualizations to understand employee information.
- Present key findings based on the cleaned dataset.

## 3. Dataset Description

The project uses an Employee Salary Dataset containing employee-related information.

**Dataset Features:**

| Column Name | Description |
|---|---|
| Name | Employee name |
| Age | Employee age |
| Salary | Employee salary |
| Join_Date | Employee joining date |
| Department | Employee department |

**Dataset Information:**

- Original dataset: 43 employee records after removing empty rows and columns.
- Cleaned dataset: 42 employee records.
- Original columns: 5
- Cleaned columns: 6 (includes Original_Salary for reference).
- Missing values were found in Age and Salary.
- One duplicate record was identified and removed.

## 4. Technologies and Libraries Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Google Colab | Development environment |
| Pandas | Data loading, cleaning, and processing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |

## 5. Project Workflow

1. **Data Loading:** Import the employee salary dataset using Pandas.
2. **Data Inspection:** Examine dataset structure, columns, data types, and missing values.
3. **Missing Value Handling:** Fill missing Age and Salary values using median imputation.
4. **Duplicate Removal:** Identify and remove duplicate records.
5. **Outlier Detection:** Detect potential salary outliers using the Interquartile Range (IQR) method.
6. **Outlier Treatment:** Apply IQR-based capping while preserving original salary values in a separate column.
7. **Data Type Correction:** Convert columns into appropriate data types.
8. **Data Visualization:** Create charts to understand department distribution, salary distribution, and the relationship between age and salary.
9. **Key Findings:** Summarize the observations from the cleaned dataset and visualizations.

## 6. Data Cleaning Summary

| Cleaning Operation | Result |
|---|---|
| Empty rows and columns | Removed |
| Missing Age values | Filled using median (36) |
| Missing Salary values | Filled using median (71,841) |
| Duplicate records | 1 duplicate removed |
| Outliers | Detected and capped using IQR |
| Data types | Corrected |

After cleaning, the dataset contains **42 employee records** with no missing values or duplicate records.

## 7. Data Visualization

The following visualizations were created using Matplotlib and Seaborn.

### 1. Employee Count by Department

A count plot was created to show the number of employees in each department.

### 2. Salary Distribution

A histogram was created to understand the distribution of employee salaries.

### 3. Age vs Salary

A scatter plot was created to visualize the relationship between employee age and salary.

## 8. Key Findings

Based on the cleaned dataset, the following observations were identified:

- **HR Department:** Has the highest employee count with 22 employees.
- **Finance Department:** Contains 10 employees.
- **IT Department:** Contains 10 employees.
- **Average Salary:** Approximately 74,140.
- **Median Salary:** 71,841.
- **Salary Range:** 61,000 to 90,802 after outlier treatment.
- **Average Employee Age:** Approximately 34.69 years.

## 9. Project Structure

```text
Data-Cleaning-and-Visualization/
│
├── Dataset/
│   ├── employee_salary_dataset.csv
│   └── cleaned_employee_salary_dataset.csv
│
├── Data_Cleaning_and_Visualization.ipynb
│
└── README.md
```

## 10. Conclusion

The Data Cleaning and Visualization Project demonstrates the practical use of Python libraries for data preprocessing and visualization.

The project involved handling missing values, removing duplicate records, detecting and treating outliers, and correcting data types.

Visualizations helped identify employee distribution across departments, understand salary distribution, and explore the relationship between age and salary.

This project provided practical experience in data cleaning, preprocessing, visualization, and extracting meaningful insights from raw data.

## Author

**Ayesha Nikhat**

- GitHub: https://github.com/ayeshanikhat12
- LinkedIn: https://www.linkedin.com/in/ayesha-nikhat-12a4aa305/
