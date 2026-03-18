# 🧹 STUDY OF DATA WRANGLING USING PYTHON

Name – Jahnvi Shukla <br/>
Branch – ENTC A3 <br/>
PRN – 25070123055 <br/>

---

## 🎯 Aim

To study and perform **data wrangling techniques using Python, Pandas, and NumPy**.

---

## 📘 Introduction

Data wrangling is the process of **cleaning, transforming, and organizing raw data** into a structured format for analysis. In real-world scenarios, datasets often contain **missing values, inconsistent formats, and incorrect entries**.

Before performing analysis, it is necessary to preprocess the data to ensure **accuracy and reliability**. Python libraries like **Pandas and NumPy** provide efficient tools for handling such tasks.

---

## 📚 Theory

Data wrangling involves several important steps to improve data quality.

One of the major issues in datasets is **missing values (NaN)**. Functions like `isna()` and `isnull()` help detect missing data, while `dropna()` removes rows containing missing values. Alternatively, `fillna()` can be used to replace missing values with mean, median, or default values.

**Data type conversion** is another important step. Sometimes numerical values are stored as strings, which can be converted using `pd.to_numeric()`.

Data inconsistency, such as different formats of text (e.g., "CSE" and "cse"), can be corrected using string functions like `.str.upper()`.

**Date formatting** is handled using `pd.to_datetime()` to convert dates into a standard format.

In large datasets, missing values can be handled using statistical methods like:

* Mean (for numerical data)
* Median
* Mode (for categorical data)

These techniques ensure that the dataset becomes **clean, consistent, and ready for analysis**.

---

## ⚙️ Procedure

1. Import **Pandas and NumPy libraries**.
2. Create a dataset with missing values.
3. Detect missing values using `isna()` and `isnull().sum()`.
4. Remove missing values using `dropna()`.
5. Replace missing values using `fillna()` with default, mean, or median values.
6. Load dataset from CSV file.
7. Replace invalid entries (like "-") with NaN.
8. Convert columns to numeric using `pd.to_numeric()`.
9. Fill missing numerical values using mean/median.
10. Standardize text data using `.str.upper()`.
11. Convert date column into datetime format using `pd.to_datetime()`.
12. Handle missing values in large dataset using mean and mode.
13. Save cleaned dataset into a new CSV file.

---

## 📊 Observations / Result

* Missing values were identified using `isna()` and `isnull().sum()`.
* Rows with missing values were removed using `dropna()`.
* Missing values were replaced using:

  * Default values
  * Mean and median values
* Invalid entries like “-” were converted to NaN.
* Data types were corrected (string → numeric).
* Inconsistent text values (e.g., "cse") were standardized to "CSE".
* Date formats were successfully converted to standard datetime format.
* In large dataset (Cars dataset):

  * Missing values in numerical columns were filled using **mean**
  * Missing categorical values were filled using **mode**

Final dataset became **clean, structured, and ready for analysis**.

---

## 🛠️ Tools / Libraries Used

* Python
* Google Colab / Jupyter Notebook
* Pandas Library
* NumPy Library

---

## 💡 Applications

* Data preprocessing in data science
* Preparing data for machine learning
* Cleaning business and survey data
* Academic data analysis
* Real-world dataset handling

---

## ✅ Advantages of Data Wrangling

1. Improves data accuracy and quality
2. Handles missing and inconsistent data
3. Makes data suitable for analysis
4. Saves time in further processing
5. Helps in better decision making
6. Essential step in data science workflow

---

## 🏁 Conclusion

Data wrangling is an essential step in data analysis that transforms raw data into a **clean and usable format**. Using Python libraries like Pandas and NumPy, tasks such as handling missing values, correcting formats, and standardizing data can be performed efficiently. This experiment demonstrates how proper data preprocessing improves the quality and reliability of analysis.

