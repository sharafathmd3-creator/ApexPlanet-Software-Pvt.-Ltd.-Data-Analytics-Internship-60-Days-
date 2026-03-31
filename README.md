# 🛍️ Task 1: Data Cleaning & Preparation  
### ApexPlanet Software Pvt. Ltd. – Data Analytics Internship  
👨‍💻 **Intern: Sharafath Mohammed**

---

## 📌 Overview  
This project focuses on cleaning and preparing a raw sales dataset.  
The goal was to convert inconsistent and error-prone data into a structured format suitable for analysis.

---

## 🎯 Key Objectives  
- Load and inspect raw data  
- Identify data quality issues  
- Perform data cleaning and preprocessing  
- Enhance dataset with useful transformations  
- Export a clean dataset  

---

## 📂 Project Files  

- `raw_sales_data.csv` → Original dataset with errors  
- `task1_data_cleaning.py` → Python script for cleaning  
- `cleaned_sales_data.csv` → Final processed dataset  
- `data_dictionary.md` → Column details and data types  

---

## ⚠️ Data Issues Identified  

- Missing values: **23**  
- Duplicate records: **5**  
- Inconsistent text formatting: **15**  
- Mixed date formats: **10**  
- Invalid price values: **3**  

---

## 🧹 Cleaning Steps Performed  

- Filled missing values using median & mode  
- Removed duplicate rows  
- Standardized text formatting  
- Converted dates to `YYYY-MM-DD` format  
- Corrected invalid price values  

---

## 📊 Before vs After  

| Metric | Before | After |
|--------|--------|-------|
| Rows | 105 | 104 |
| Columns | 17 | 21 |
| Missing Values | 23 | 0 ✅ |
| Duplicates | 5 | 0 ✅ |

---

## 🛠️ Tools & Technologies  

- Python 3.14  
- Pandas  
- NumPy  

---

## 🚀 Outcome  
Successfully transformed raw data into a clean, structured dataset ready for analysis and visualization.

---

⭐ *Part of ApexPlanet Data Analytics Internship (Task 1 of 5)*
