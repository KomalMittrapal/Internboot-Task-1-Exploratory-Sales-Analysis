# Internboot-Task-1-Exploratory-Sales-Analysis
EDA of Time-Series Sales Dataset Using Python, Pandas, and Matplotlib

# Task 1 – Exploratory Sales Analysis - Internboot Data Analyst Internship  

## 📌 Project Overview  
This repository contains my completed work for **Beginner Level Task 1: Exploratory Sales Analysis**, assigned as part of my **Data Analyst Internship at Internboot**.

The goal of this task is to perform **Exploratory Data Analysis (EDA)** on part of the **Store Sales Time-Series Dataset (Kaggle)** to understand trends, seasonality, patterns, and summary statistics.  
The entire analysis is done using **Python, Pandas, Matplotlib, and Seaborn**.

## 🧰 Tech Stack  
- **Python 3**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- (Optional) Jupyter Notebook or VS Code  

## 🧪 Task Objectives  
The following steps were performed in this project:

### ✔️ **1. Data Loading**
- Imported dataset using `Pandas`
- Checked dimensions, datatypes, and structure

### ✔️ **2. Data Cleaning**
- Parsed the `date` column into datetime format  
- Generated additional time features:  
  - `year`, `month`, `day`, `weekday`, `month_name`  
- Removed invalid date entries  
- Saved cleaned dataset

### ✔️ **3. Descriptive Statistics**
- Mean, median, mode  
- Frequency counts  
- Missing value analysis  
- Summary statistics for numeric/time features  

### ✔️ **4. Exploratory Visualizations**
Using **Matplotlib** & **Seaborn**:

- 📈 Events per year  
- 📊 Events by type  
- 🗺️ Top 15 locales  
- 📅 Month-wise seasonality  
- 🕒 Weekday distribution  
- 📆 Histogram of day-of-month  

All plots are saved inside the `task1_plots/` folder.

## 🏁 Deliverables

| File Name | Description |
|------------|--------------|
| `holidays_events.csv` | Original dataset used for analysis |
| `Task 1_Exploratory_Sales_Analysis.ipynb` | Jupyter Notebook |
| `task1_plots` | All generated files for reporting |
| `README.md` | This documentation file) |
| `TASK_1_Output_Files` | Contain all Output Files |

## 📊 Key Insights (Short Summary)
- Dataset covers **2012–2017**.  
- Highest event frequency observed in **2016**.  
- **"Holiday"** is the most common event type.  
- **Ecuador** appears as a dominant locale due to country-level records.  
- Events show noticeable **monthly** and **weekday-based** variation.  
- Strong foundations for further time-series forecasting tasks.

For the full analysis, refer to the script/notebook and summary file.

# 🤝 Acknowledgements

This project is completed as part of the Internboot Data Analyst Internship Program.
Grateful for the opportunity to learn and grow.

---
*Created by Komal for the Data Analyst Internship Program.*

