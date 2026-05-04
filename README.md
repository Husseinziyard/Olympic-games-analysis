# 🏅 Olympic Games Data Analysis

An interactive Power BI dashboard analyzing **All-time Olympic Games medal data** for both Summer and Winter Olympics — covering national performance, medal distribution trends, and participation-success correlations.

---

## 📌 Project Overview

This project explores historical Olympic medal data sourced from Wikipedia's *All-time Olympic Games Medal Table*. The goal was to build a dynamic, filterable Power BI dashboard that gives users a comprehensive view of how countries have performed across Olympic history.

---

## 📊 Dashboard Features

| Visualization | Description |
|---|---|
| Total Medals by Season (Bar Chart) | Compares Summer vs. Winter medal totals for top 10 nations |
| Medal Type Comparison (Pie Charts) | Shows gold, silver, bronze distribution per season |
| Medal Distribution by Country (100% Stacked Area) | Medal type share across top-performing nations |
| Participation vs. Medal Rate (Donut Charts) | Efficiency of participation vs. medals earned |
| KPI Summary Cards | High-level stats: total games played, total medals won |
| Country Slicer | Interactive dropdown to filter all visuals by nation (IOC code) |

---

## 🔍 Key Findings

- **Summer Dominance:** USA, China, and Russia lead Summer Olympics medal tallies.
- **Winter Dominance:** Norway and Germany excel in Winter events (cross-country skiing, biathlon, alpine).
- **Dual Performers:** Germany, Canada, and Sweden are competitive in both seasons.
- **Experience Correlation:** Long-term participation positively correlates with overall medal success.
- **Strategic Focus:** Countries like China cluster medals in specific sports (diving, table tennis), while others show broader competitiveness.

---

## 🛠️ Tech Stack

- **Data Source:** Wikipedia – All-time Olympic Games Medal Table
- **Data Processing:** Microsoft Excel (.xlsx)
- **Visualization:** Microsoft Power BI
- **Preprocessing:** Missing value handling, IOC code standardization, numeric formatting

---

## 📁 Repository Structure

```
olympic-games-analysis/
├── data/
│   └── olympic_medals.xlsx        # Cleaned dataset
├── dashboard/
│   └── olympic_dashboard.pbix     # Power BI dashboard file
├── report/
│   └── Olympic_Games_Data_Analysis.pdf
└── README.md
```

---

## 🚀 How to Run

1. Download and install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Open `dashboard/olympic_dashboard.pbix`.
3. Use the **Country Slicer** dropdown to filter by any nation (IOC code).
4. Click any chart element to cross-filter all other visuals.

---

## 📚 Data Source

- [Wikipedia – All-time Olympic Games Medal Table](https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table)

---
