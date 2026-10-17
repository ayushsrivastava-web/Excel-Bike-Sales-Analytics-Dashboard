# 📊 Bike Sales Data Cleaning, EDA & Interactive Dashboard


## 📌 Project Overview
-This project provides an end-to-end data analysis workflow in Microsoft Excel using a Bike Sales dataset. The primary goal is to analyze customer demographics (income, age groups, commute distance, region, and marital status) to understand the key factors influencing whether a customer purchases a bike.
-The repository covers Data Cleaning, Exploratory Data Analysis (EDA) using Pivot Tables, and an Interactive Executive Dashboard with dynamic filters.

---

## 📁 Repository Structure
```text
├── Bike Sales Analysis & Customer Insights Dashboard.xlsx  # Main workbook (Data Cleaning, Pivot Tables, & Dashboard)
├── screenshots/               # Visual previews of the dashboard and charts
│   ├── dashboard_overview.png
│   └── eda_pivot_charts.png
└── README.md                  # Project documentation
```

---

## 📊 Data Source & Dataset
-The raw dataset used for this project was obtained from:
-Dataset Link / Source: -  [View Raw Dataset on GitHub](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)
-(Note: The original dataset contains customer demographic information including income, marital status, education, occupation, region, and bike purchase status.)

---

## 🛠️ Data Processing & Workflow

### 1. 🧹 Data Cleaning & Preprocessing
```text
-The raw dataset (Data sheet) was sanitized to ensure accurate metrics:
-Handling Duplicates: Identified and removed duplicate records to prevent skewed demographic totals.
-Text Standardization: Standardized coded categorical values (e.g., converted Marital Status code M to Married and S to Single; Gender code M/F to Male/Female).
-Custom Calculation (Age Brackets): Applied nested IF formulas to categorize continuous age values into meaningful demographic buckets:
=IF(L2>54, "Old", IF(L2>=31, "Middle Age", IF(L2<31, "Adolescent", "Invalid")))
-Number & Currency Formatting: Formatted Income values into currency format and removed redundant trailing decimals from commute distance fields.
```

---

## 2. 🔍 Exploratory Data Analysis (EDA)
```text
-Using Pivot Tables and Pivot Charts, customer purchasing behavior was analyzed across multiple key dimensions:
-Income vs. Bike Purchase: Compared average income levels between buyers and non-buyers across genders.
-Commute Distance Impact: Tracked bike purchasing trends based on daily commuting distance (0-1 Miles, 1-2 Miles, 2-5 Miles, 5-10 Miles, 10+ Miles).
-Age Group Segmentation: Evaluated bike purchase rates across age brackets (Adolescent, Middle Age, and Old).
```

## 3. 💡 Key Insights & Findings
```text
-Income Influence: Customers with higher average income are significantly more likely to purchase a bicycle across both male and female groups.
-Short Commutes Drive Sales: Customers with shorter commute distances (specifically 0–1 Miles) show the highest likelihood of purchasing bikes. Conversion rates decline sharply as commute distance exceeds 5 miles.
-Primary Target Segment: The Middle Age group (ages 31–54) represents the largest buyer demographic, outperforming adolescents and seniors in total purchase volume.
```

## 4. 📉 Interactive Executive Dashboard
```text
-An interactive dashboard was built in Excel to consolidate key visual insights:
-Dynamic Filters (Slicers): Integrated interactive slicers for Region (Europe, North America, Pacific), Education, and Marital Status to allow instant cross-filtering.
-Visual Representation: Features dynamic charts linking Income, Commute Distance, and Age Brackets directly to bike purchase counts.
```

---

## 🚀 How to View & Use This Project
```text
-Clone or download this repository:
-git clone https://github.com/ayushsrivastava-web/Excel-Bike-Sales-Analytics-Dashboard.git
-Open Excel Project Dataset.xlsx using Microsoft Excel 2016 or newer.
-Navigate to the Dashboard worksheet.
-Interact with the Slicers on the side to filter data dynamically by Region, Education level, and Marital Status.
```

---

## 🧰 Tools & Formulas Used
```text
-Tool: Microsoft Excel
-Formulas: Nested IF logic (for Age Grouping), AVERAGE, COUNTIF
-Features: Pivot Tables, Pivot Charts, Custom Slicers, Data Cleansing, Formatting
```
---

## 🤝 Connect with Me
-Email: ayushkrsrivastava374@gmail.com

```
