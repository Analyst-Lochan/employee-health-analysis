
# 🧠 Employee Health Data Cleaning & Dashboard Project

This project is a demonstration of my Excel-based data analysis skills applied to a simulated real-world employee health dataset. It includes a full data cleaning process, derived metrics, pivot table analysis, and dashboard setup. This work showcases my readiness for data analyst roles requiring precision, attention to detail, and actionable insight generation.

---

## 📁 Repository Structure

```
employee-health-data-cleaning-dashboard/
│
├── Uncleaned_Employee_Health_Data.xlsx     # Raw data with duplicates, typos, and inconsistencies
│   Employee_Health_Data_Cleaned.xlsx       # Cleaned data with formulas, pivot tables, and derived columns
│
├── dashboard_screenshot.png                # chart-based summary of the dashboard 
│
└── README.md                               # Project documentation
```

---

## 🎯 Project Objectives

- Clean a messy employee health dataset to make it usable
- Derive meaningful metrics using Excel formulas
- Categorize key variables (e.g., WorkHours, SleepHours, HeartRate, etc.)
- Build a pivot table to summarize departmental insights
- Create a dashboard layout for HR health monitoring

---

## 🧹 Data Cleaning Tasks Performed

- Removed ~500 duplicate rows from 10,500 records
- Corrected inconsistent labels (e.g., `Fmale` → `Female`, `Hr` → `HR`)
- Standardized case formatting and removed extra spaces
- Categorized numeric values using Excel `IF()` logic:
  - `WorkHoursStatus` — Overloaded / Normal / Others
  - `StressLevelStatus` — High / Moderate / Low
  - `SleepHoursStatus` — Well Rested / Moderate / Sleep Deprived
  - `HeartRateStatus` — High / Normal / Low
  - `StepCountStatus` — Highly Active / Active / Low Active / Sedentary
  - `ProductivityScoreStatus` — Excellent / Good / Average / Poor
- Calculated `NoOfDays` = LastLogin - DateOfJoining

---

## 📊 Pivot Table Insights

A pivot table was created to:
- Analyze average WorkHours by Department
- Segment employees by Stress Level and Productivity Score
- Observe StepCount activity trends

---

## 📈 Dashboard (in Excel)

The `DashBoard` sheet serves as a layout for:
- KPI cards (Avg WorkHours, Sleep, Stress, Productivity)
- Department-level breakdowns
- Visuals like bar charts, pie charts, and slicers (user can add)

---

## 🛠️ Tools Used

- **Microsoft Excel**
  - Advanced Formulas
  - Data Validation & Cleaning
  - Pivot Tables
  - Dashboard Setup

---

## 🧠 Skills Demonstrated

- Data Cleaning and Preprocessing
- Categorization of Numeric & Text Data
- Derived Column Creation
- Analytical Thinking for KPI Extraction
- Excel Dashboard Design

---

## 💼 About Me

I’m an aspiring Data Analyst skilled in Excel, SQL, and Python. This project reflects my ability to work with raw business data, clean it methodically, and extract actionable insights through dashboarding.

---

## 📌 How to Explore

1. Open the uncleaned dataset to view raw data issues
2. Compare with the cleaned version (`Main` sheet)
3. Explore the Pivot Table and use slicers for insights
4. Extend the Dashboard layout by adding visual charts
