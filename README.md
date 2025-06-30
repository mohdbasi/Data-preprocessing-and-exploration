# 🍽️ Restaurant Ratings - Data Exploration and Preprocessing

This notebook contains **Task 1** from my Data Science internship, where I performed detailed **Exploratory Data Analysis (EDA)** and **Data Preprocessing** on a restaurant dataset.

## 🔍 Task Objective

> Analyze and prepare the dataset by understanding its structure, handling missing values, correcting data types, and exploring the target variable.

---

## Key Steps Performed

### 1. Dataset Overview
- Loaded CSV data using `pandas`
- Checked the number of rows and columns (`df.shape`)
- Previewed the first few records with `df.head()`

### 2. Missing Value Treatment
- Identified 9 missing values in the `Cuisines` column
- Handled them using `fillna("Unknown")`

### 3. Data Type Conversion
- Converted 4 columns (`Has Table booking`, `Has Online delivery`, `Is delivering now`, `Switch to order menu`) from `"Yes"/"No"` (object) to `True/False` (boolean)

### 4. Target Variable Analysis - `Aggregate rating`
- Counted and visualized rating distribution
- Identified a high number of unrated entries (`0.0`)
- Noted class imbalance, with most ratings falling between 3.0 and 4.0

---

## Tools Used
- Python
- Pandas
- Jupyter Notebook

---

