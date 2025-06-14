# ✈️ Airline Passenger Survey Profiling & Data Cleansing

📅 **Timeline:** Fall 2024  
🔍 **Objective:** Clean, prepare, and profile airline passenger satisfaction data—focused on Business Class travelers—to uncover service improvement opportunities.  
🧰 **Tools:** Python · Pandas · NumPy · Matplotlib · Data Profiling

---

## 🧠 Project Overview

As the airline industry rebounds post-COVID, understanding customer satisfaction is critical. This project focuses on preparing a domestic airline’s **passenger satisfaction survey dataset** for analysis. We isolate **Business Class passengers**, conduct deep data profiling, and perform a complete cleansing to ensure data integrity before modeling.

---

## 📂 Data Source

- `Passengers_Satisfaction_Survey.csv`: Raw airline passenger survey dataset
- `Project_2_Group7.csv`: Cleaned version ready for modeling
- `Code.py`: Python script for profiling, cleaning, and exporting

---

## 📊 Step 1: Data Profiling (Subset: Business Class)

### 📁 Created Subset: `df_Business`
Filtered the dataset to focus on Business Class passengers only.

### 🧾 Profiled:
- Total rows & columns
- Data types of all fields
- Unique values per column
- Missing values summary
- Descriptive stats (mean, median, std)
- Frequency distribution (categorical fields)
- Count of fully duplicated rows

### 🛑 Issues Identified:
- Inconsistent column naming (e.g., whitespaces, casing)
- Missing values across key variables (e.g., age, flight distance)
- Improperly formatted values (e.g., `Gender` with trailing spaces)
- Fully duplicated records
- Incorrect data types (e.g., satisfaction columns as strings)

---

## 🧼 Step 2: Data Cleaning

### ✅ Actions Taken:
- Dropped unnecessary `Class` column
- Renamed columns to lowercase + snake_case for consistency
- Stripped white space and corrected value formatting (e.g., gender, satisfaction)
- Converted column types to appropriate formats
- Imputed or dropped missing values
- Removed fully duplicated observations

✅ **Final cleaned dataset** had:
- `0` missing values  
- `0` fully duplicated rows  
- Valid, consistent formatting across all features

---

## 📤 Output Files
- `Project_2_Group7.csv`: Final cleaned dataset
- `Code.py`: Full script with profiling + cleaning logic
- (Optional) Add exploratory plots like missingness heatmaps, satisfaction bar charts

