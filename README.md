# 🧹 Retail Data Cleaning & Outlier Handling  

![Python](https://img.shields.io/badge/Python-Data%20Science-blue)
![Project](https://img.shields.io/badge/Project-Data%20Cleaning-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Intermediate-purple)
![Focus](https://img.shields.io/badge/Focus-Data%20Quality-yellow)

---

## 👨‍💻 Author

**Ashish Jonnada**
🎓 B.Tech CSE (AI & Data Science) -- Marwadi University

🔗 **LinkedIn:** [Ashish Jonnada](https://www.linkedin.com/in/jonnada-ashish)

------------------------------------------------------------------------

## 📌 Project Overview

This project focuses on improving the quality and reliability of a
retail transaction dataset through systematic data cleaning techniques.
Real-world datasets often contain missing values, duplicate records,
inconsistent formats, and extreme values that can negatively impact
analysis and machine learning performance.

The goal of this project is to transform raw retail data into a clean,
structured, and analysis-ready dataset suitable for further analytical
or machine learning applications.

------------------------------------------------------------------------

## ⚠️ Problem Statement

Retail transaction datasets frequently contain incomplete records,
duplicated entries, inconsistent formatting, and outliers that reduce
data accuracy and reliability. If not handled properly, these issues can
lead to misleading insights and poor analytical outcomes.

This project aims to clean and standardize the dataset to ensure it is
accurate, consistent, and ready for reliable analysis.

------------------------------------------------------------------------

## 🎯 Project Objectives

-   Identify and handle missing values
-   Remove duplicate records to ensure data integrity
-   Detect and treat outliers using statistical method
-   Standardize data formats for consistency
-   Prepare the dataset for analysis and future ML applications

------------------------------------------------------------------------

## 🧠 Methodology

### 🔍 Data Understanding

-   Explored dataset structure and data types
-   Analyzed missing values and inconsistencies

### 🧹 Missing Value Handling

-   Removed completely empty rows
-   Removed rows with more than 70% missing values
-   Filled remaining missing values appropriately

### 🗂️ Duplicate Handling

-   Identified duplicate records
-   Removed redundant entries

### 📉 Outlier Detection (IQR Method)

-   Applied Interquartile Range method
-   Treated extreme values in:
    -   `Price_Per_Unit`
    -   `Total_Spent`
-   Validated using boxplots

### ⚙️ Data Standardization

-   Corrected data types
-   Standardized formatting
-   Ensured dataset consistency

------------------------------------------------------------------------

## 📊 Dataset Cleaning Summary

| 🏷 Stage | 📈 Rows |
|----------|--------|
| 📂 Raw Dataset | **13,833** |
| 🧹 After Removing Empty Rows | **12,106** |
| ⚠️ After Removing >70% Missing Rows | **12,008** |
| 🔁 After Duplicate Removal | **10,974** |
| 📉 After Outlier Handling | **10,399** |

**Total Rows Removed:** **3,434**  
**Final Dataset Size:** **10,399 rows × 11 columns**

------------------------------------------------------------------------

## 🔎 Key Insights

-   Missing values were concentrated in incomplete records
-   Removing highly sparse rows improved data consistency
-   Duplicate transactions were minimal but important to remove
-   Outlier handling stabilized numeric distributions
-   Majority of valid transactions were retained

------------------------------------------------------------------------

## 🛠 Tools & Technologies Used

-   Python
-   Pandas 
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## 🏁 Conclusion

Through structured data cleaning and validation, the dataset was
transformed from a raw and inconsistent state into a reliable and
analysis-ready format.

This project highlights the importance of proper data preparation before
analysis or machine learning, demonstrating how improved data quality
leads to more accurate insights and better model performance.
