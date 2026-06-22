# SCT_DA_2 - Data Cleaning and Preparation

## 📋 Task Overview
**SkillCraft Technology - Data Analyst Internship | Task 2**

Load a dataset into Python using Pandas, perform data cleaning and preparation, and export the cleaned data to a new CSV file.

## 🎯 Objectives
- Load the Superstore Sales Dataset using Pandas
- Identify and handle missing values
- Drop duplicate rows
- Convert data types (date columns, postal code)
- Export cleaned dataset to a new CSV file

## 🛠️ Tools & Libraries
- Python 3.14
- Pandas
- Jupyter Notebook (VS Code)

## 📊 Dataset
- **Source:** Sample - Superstore Sales Dataset
- **Records:** 9,994 rows × 21 columns

## ✅ Steps Performed
1. Loaded dataset using `pd.read_csv()`
2. Checked missing values using `df.isnull().sum()`
3. Handled missing values (numeric → median, text → 'Unknown')
4. Dropped duplicate rows using `df.drop_duplicates()`
5. Converted `Order Date` & `Ship Date` from string to datetime
6. Converted `Postal Code` from integer to string
7. Exported cleaned data as `Cleaned_Superstore.csv`

## 📁 Files
| File | Description |
|------|-------------|
| `task2.ipynb` | Jupyter Notebook with complete code |
| `Cleaned_Superstore.csv` | Exported cleaned dataset |
