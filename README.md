
# 📊 US Wage & Employment Trends Dashboard (Excel + Formulas)

## 👤 Author
**Siddharth Abhiram**

---

## 🧠 Project Overview
This project analyzes wage and employment statistics across U.S. industries and states from 2017–2020. The goal is to help high school seniors explore career opportunities through an interactive dashboard.

Unlike typical Excel dashboards built only with PivotTables, this one incorporates **Excel formulas**, allowing deeper comparison and calculated analysis across industries.

---

## 🎯 Dashboard Questions Answered
✅ Which industries offer the highest annual wages?  
✅ Are there meaningful year-over-year employment trends?  
✅ Which states provide the best opportunities per industry?  
✅ How large is each sector’s employment share?

---

## 🧾 Dataset Structure
The dataset includes:

| Column | Description |
|--------|-------------|
| Year | 2017–2020 data points |
| Industry | Manufacturing, Finance, etc. |
| State | U.S. state |
| Establishments | Number of registered businesses |
| Employees | Total employees in that industry |
| Avg Annual Wage | Average yearly compensation |

---

## 🧮 Excel Formulas Used
To calculate metrics and comparisons, the following formulas were used:

### 📌 Summary Metrics
- `AVERAGEIF()` for wage averages by industry
- `COUNTIFS()` for establishment counts
- `SUMIFS()` for employee totals

### 📌 Conditional Calculations
- `IF()` for threshold comparisons
- `ROUND()` to improve readability
- `% of Total` calculations using ratio formulas

### 📌 Lookup Logic
- `XLOOKUP()` and `VLOOKUP()` for state-industry matching
- `INDEX/MATCH` for flexible referencing

These allow comparisons **without** depending exclusively on pivot aggregations.

---

## 📈 Visual Components Used
This dashboard includes:

✔ Industry comparison bars  
✔ Employment share donut chart  
✔ Wage trend columns (multi-year)  
✔ Interactive U.S. map by wage intensity  
✔ Industries highlighted on selection  

---

## 🛠️ Tools & Skills
| Skill | Description |
|-------|-------------|
| Excel Formulas | SUMIFS(), AVERAGEIF(), COUNTIFS(), XLOOKUP |
| Data Cleaning | Removing errors, normalizing wages |
| Dashboard Design | Layout, formatting, chart selection |
| Interactive Analytics | Slicers, dynamic ranges |

---

## 🧠 Insights Gained
- Finance consistently offers top wages
- Manufacturing employs a large share of workers nationally
- State-level wage differences are significant
- Some industries fluctuate year-to-year

---

## 🚀 Why This Matters
Students can explore:
- Which careers pay best
- Where jobs are located
- How industries change over time

This encourages **data-driven decision-making**.

---

## 🗃 Repository Structure
