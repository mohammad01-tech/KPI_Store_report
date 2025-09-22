# 🧸 Toy Store KPI Report (Power BI Project)

## 📌 Project Overview
The goal of this project was to **build a simple, interactive KPI report** to track key metrics and explore high-level trends for Maven Toys.  

The project walks through the full Power BI workflow: connecting and profiling raw data, building a relational model, creating calculated measures, and designing an interactive report.

---

## 🎯 Project Objectives

### **Objective 1: Connect & Profile the Data**
- Connected to the **sales, products, stores, and calendar** CSV files  
- Reviewed table columns, checked for blanks/nulls, validated data types  
- Identified **primary and foreign keys**  
- Profiled the data:  
  - Number of transactions recorded  
  - Number of stores operated by Maven Toys  
  - Lowest & highest priced products  
- Added calculated columns in the calendar table for:  
  - *Start of Month*  
  - *Start of Week*  

---
### **Objective 3: Add Calculated Measures & Fields**
- Added calculated columns in Sales:  
  - Cost  
  - Price  
  - Revenue (Price × Quantity)  
  - Profit (Revenue − Cost)  
- Defined measures:  
  - **Total Orders** (count of orders)  
  - **Total Revenue** (sum of revenue)  
  - **Total Profit** (sum of profit)  
- Bonus: Created additional measures without referencing calculated columns  

---
### **Objective 4: Build the Interactive Report**

**KPI Cards:**

Total Orders by Start of Month (41,830 on Sept 1, 2023)

Total Revenue by Start of Month ($658,194 on Sept 1, 2023)

Total Profit by Start of Month ($180.45K on Sept 1, 2023)

**Slicers**:

Store Location (Airport, Commercial, Downtown, Residential)

**Charts**:

Revenue by Top 10 Store Cities (Bar Chart)

Revenue by Start of Month (Line Chart with Date Hierarchy)

Orders by Product Category (Bar Chart)

Quick Insight Section (added inside the report):

Ciudad de México is the top revenue contributor ($1.65M)

Toys lead in order volume (221K orders)

Electronics show the lowest order count (99K)

**Final touches**:

Used custom layout shapes for sections

Added store logo image for branding

Applied dark theme with consistent formatting and alignment

---
## 📊 Dashboard Highlights
- 📍 **Ciudad de México** is the highest revenue contributor with **$1.65M**  
- 🧸 **Toys** category leads in order volume (**221K orders**)  
- 🎨 **Arts & Crafts** category follows closely (**220K orders**)  
- 📉 **Electronics** recorded the lowest order volume (**99K orders**)  
- 💰 **Total Revenue** for Sept 1, 2023: **$658,194**  
- 📦 **Total Orders** for Sept 1, 2023: **41,830**  
- 🏆 **Total Profit** for Sept 1, 2023: **$180.45K** 