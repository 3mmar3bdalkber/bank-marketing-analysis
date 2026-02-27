<h1 align="center"> Bank Marketing Dashboard (Excel + Power Pivot)</h1>

<p align="center">
  An interactive Excel dashboard built with <strong>Power Pivot</strong> to analyze direct marketing campaigns of a Portuguese banking institution.<br/>
  Explore 45,211 phone contacts and discover key drivers of term deposit subscriptions.
</p>

<p align="center">
  <!-- Badges -->
  <a href="https://www.microsoft.com/en-us/microsoft-365/excel"><img src="https://img.shields.io/badge/Excel-2016+-217346?logo=microsoft-excel&logoColor=white" alt="Excel"></a>
  <a href="https://docs.microsoft.com/en-us/power-pivot/"><img src="https://img.shields.io/badge/Power_Pivot-DAX-0078D4?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMiAxMkgydjJoMjB2LTJ6bTAgNEgydjJoMjB2LTJ6bTAtOEgydjJoMjB2LTJ6bTAtNEgydjJoMjB2LTJ6Ii8+PC9zdmc+" alt="Power Pivot"></a>
  <a href="https://archive.ics.uci.edu/ml/datasets/Bank+Marketing"><img src="https://img.shields.io/badge/Dataset-UCI-FF6F00?logo=databricks" alt="UCI Dataset"></a>
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen" alt="Status">
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#demo">Demo</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#project-structure">Structure</a> •
  <a href="#key-insights">Insights</a>
</p>

---

## Features

### **Interactive Dashboard**
- **KPI Cards** – Total contacts, total subscriptions, conversion rate.
- **Subscriptions by Job** – Bar chart showing which occupations are most responsive.
- **Seasonal Trends** – Line chart of subscriptions across months.
- **Balance Category vs Subscription** – Donut chart revealing the influence of account balance.
- **Contact Type Effectiveness** – Stacked bar comparing cellular, telephone, and unknown methods.
- **Dynamic Slicers** – Filter by age group, marital status, education, month, and more – all charts update instantly.

### **Data Modeling**
- **Power Pivot Data Model** – Efficient in‑memory analytics.
- **DAX Calculated Columns** – Added `Age Group`, `Balance Category`, `Month Name`, `Month Number`.
- **Key Measures** – `Total Contacts`, `Subscribed`, `Conversion Rate`.

### **Analysis Ready**
- Cleaned and handled `"unknown"` values.
- Duplicates removed, outliers binned.
- Derived categories for deeper insights.

---

## Demo

<p align="center">
  <img src="dashboard/screenshot.png" width="80%" alt="Dashboard Preview"/>
  <br/>
  <em>Click the image to download the Excel file and try it yourself!</em>
</p>

**[Download the Excel Dashboard](dashboard/BankMarketing_Dashboard.xlsx)**  

---

## Tech Stack

| Component        | Technology                                     |
|------------------|------------------------------------------------|
| **Data Modeling**| Power Pivot (Excel) with DAX                   |
| **Visualization**| PivotTables, PivotCharts, Slicers, Timelines   |
| **Data Source**  | [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) (45,211 records) |
| **Version**      | Excel 2016+ (compatible with Office 365)       |

---

## Project Structure

```bash
bank-marketing-dashboard/
├── data/
│ └── Bank After Analysis.csv # Cleaned dataset
├── dashboard/
│ ├── BankMarketing_Dashboard.xlsx
│ └── screenshot.png
└──README.md # You are here
```

---

## Key Insights

- **Job Type**: Students and retired clients have the highest subscription rates.
- **Seasonality**: March, September, and December see peak subscriptions.
- **Account Balance**: Clients with medium/high balances (>1000€) are more likely to subscribe; those with debt are least likely.
- **Contact Method**: Cellular calls outperform telephone contacts by a wide margin.

---
