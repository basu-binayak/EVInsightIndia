# **EVInsightIndia 🚗⚡**

**Market Analysis of Electric & Hybrid Vehicles in India for AtliQ Motors**

---

## 📌 **Project Overview**

This project presents an end-to-end data analytics study of the Indian electric and hybrid vehicle market for AtliQ Motors’ expansion strategy. Using Power BI, the analysis explores EV adoption patterns, market performance of manufacturers, state-wise trends, and growth opportunities to support strategic decisions.

---

## 📘 **Problem Statement**

AtliQ Motors is an automotive giant from the USA specializing in electric vehicles (EV). Over the last 5 years, the company expanded its EV and hybrid market share to **25% in North America** .

As part of global expansion, AtliQ Motors plans to launch its bestselling EV models in **India** , where its current market share is **less than 2%** . Before proceeding, **Bruce Haryali** , the Chief of AtliQ Motors India, requested a detailed market study of the existing Indian EV/Hybrid market.

He assigned this task to the data analytics team, where **Peter Pandey** , a data analyst, is responsible for uncovering insights using available EV sales data.

This repository contains all resources, datasets, dashboards, and documentation related to this analysis.

---

## 📁 **Dataset Metadata**

### **1. electric_vehicle_sales_by_state.csv**

- **date** – Monthly date of record (DD-MMM-YY)
- **state** – Indian state where sales were recorded
- **vehicle_category** – 2-Wheeler or 4-Wheeler
- **electric_vehicles_sold** – EV units sold in that state & category
- **total_vehicles_sold** – Total vehicles sold (EV + non-EV)

### **2. electric_vehicle_sales_by_makers.csv**

- **date** – Monthly date of record
- **vehicle_category** – 2-Wheeler or 4-Wheeler
- **maker** – EV manufacturer/brand
- **electric_vehicles_sold** – Units sold by the maker in that month and category

### **3. dim_date.csv**

- **date** – Date reference (DD-MMM-YY)
- **fiscal_year** – Follows Indian FY (April → March)
- **quarter** – Q1, Q2, Q3, or Q4

---

## 📊 **Key Business Metrics**

### **1. Penetration Rate**

Measures EV adoption relative to total vehicle sales:

```
Penetration Rate = (Electric Vehicles Sold / Total Vehicles Sold) * 100
```

### **2. Compound Annual Growth Rate (CAGR)**

Shows long-term growth trend:

```
CAGR = [(Ending Value / Beginning Value) ^ (1/n)] - 1
```

---

## 🎯 **Project Goals**

This analysis aims to uncover:

- State-wise EV adoption and market potential
- Segment performance (2W vs 4W)
- Maker-wise sales leadership and competition
- Yearly and quarterly EV growth trends
- EV penetration across categories and regions
- Recommendations for AtliQ Motors’ India entry strategy

---

## 🛠 **Tools & Technologies**

- **Power BI** – Primary tool for modeling, analysis, and dashboard creation
- **Power Query** – Data cleaning and transformation
- **DAX** – Custom calculations and KPIs
- **CSV datasets** – Source files for analysis

---

## 📂 **Repository Structure**

```
EVInsightIndia/
│
├── data/
│   ├── electric_vehicle_sales_by_state.csv
│   ├── electric_vehicle_sales_by_makers.csv
│   └── dim_date.csv
│
├── powerbi/
│   └── EVInsightIndia_Dashboard.pbix
│
├── reports/
│   └── insights_summary.pdf
│
├── visuals/
│   └── screenshots_of_dashboard/
│
└── README.md
```

---

## 📥 **How to Download Resources from This Repository**

You can download the datasets or entire project in two ways:

### **Option 1: Download the Entire Repo**

- Click the **Code** (green button)
- Select **Download ZIP**
- Extract the folder locally

### **Option 2: Download a Single File**

- Navigate to the file
- Click the **Download raw file** button

---

## 📈 **Deliverables**

This project provides:

- Clean and well-modeled datasets
- Power BI dashboard with actionable insights
- Key metrics such as penetration rate, CAGR, growth trends
- Recommendations for AtliQ Motors’ India launch

---

## ⭐ **Conclusion**

This study equips AtliQ Motors with data-backed insights to evaluate market potential, understand competition, and identify strategic opportunities in the Indian EV/Hybrid space. It serves as a crucial foundation for market entry decisions and long-term planning.
