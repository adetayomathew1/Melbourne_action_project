# Melbourne_action_project
# 🏠 Melbourne Auction Analysis Dashboard (Virtual Client Project)

**Client:** RealEstate Insights Australia  
**Role:** Data Analyst (Virtual Client Project)  
**Tools:** Microsoft Excel · VBA · PivotTables · Slicers · Conditional Formatting

---

## 📘 Project Overview

This project simulates a real-world consulting engagement with **RealEstate Insights Australia**, focused on analyzing the **Melbourne housing and auction market**.  
The goal was to design and implement an **interactive Excel dashboard** to track key housing metrics — including average house and unit prices, suburb performance, and clearance rates.

---

## 🎯 Project Objectives

- Build an interactive and user-friendly Excel dashboard for quick insights into the Melbourne housing market.  
- Enable data exploration by council areas and months using slicers.  
- Automate data refresh and workbook management using VBA macros.  
- Present metrics such as **Top Suburb House Prices**, **Average Unit Price**, and **Clearance Rates** clearly and professionally.

---

## 🧩 Process & Implementation

### **Step 1 – Dashboard Design and Layout**
- Duplicated existing design tiles and customized dimensions (7.3 cm × 9.5 cm) to add a new **Top Suburb House Prices** section.
- Applied alignment and formatting for consistent dashboard structure.

### **Step 2 – Add Charts**
- Integrated charts from multiple worksheets:
  - **Melbourne Trends** → Melbourne Average Price tile  
  - **Suburb Price** → Suburb Average Price tile  
  - **Clearance Rates** → Clearance Rate tile  
- Used custom house and unit icons to label chart series for visual clarity.

### **Step 3 – Add Additional Metrics**
- Inserted **PivotTable from Top Suburbs** as a linked image to dynamically update inside the dashboard.
- Linked **Average Unit Price** data from the Calcs sheet using `AVERAGEIFS` for 2017–2018 comparisons.
- Applied **custom number formatting** to display up (↑) and down (↓) arrows for price changes.
- Added **clearance rate summary** using live linked images aligned with KPI tiles.

### **Step 4 – Add Slicers (Interactivity)**
- Added slicers for **Month** and **Council Area** to make the dashboard interactive.
- Linked slicers to all PivotTables (except pvtTrends) for synchronized filtering.
- Customized slicer styles (Light Blue Slicer Dark 1) and created a new “Dashboard” style with smaller fonts and no borders.
- Adjusted slicer dimensions and placement for a clean layout:
  - Month slicer: 4×4 cm (4 columns)
  - Council Area slicer: 9.4×4 cm (hidden header, hide items with no data)

### **Step 5 – Automation and Protection**
- Added **hyperlinks** for easy navigation between Home, Data, and Dashboard sheets.
- Recorded and edited **VBA macros** to:
  - Refresh all datasets.
  - Close the workbook through a custom `CloseWB` macro.
- **Protected the dashboard sheet** to prevent accidental edits while keeping slicers active.
- Verified functionality of all interactive elements.

---

## 📊 Dashboard Features

- **Dynamic Visuals:** Real-time charts for housing trends and suburb performance.  
- **KPIs:** Top suburb house prices, average unit price, clearance rates.  
- **Automation:** Macros to refresh and close the workbook with one click.  
- **User Interaction:** Slicers for filtering by month and council area.  
- **Data Protection:** Locked layout to maintain dashboard integrity.

---

## 🧠 Skills Demonstrated

- Excel Dashboard Design  
- PivotTables and Linked Images  
- Conditional Formatting  
- VBA Macro Automation  
- Data Visualization  
- Interactive Reporting  
- Business Analytics

---

## 📈 Key Takeaways

- Learned how to combine **Excel visualization**, **automation**, and **interactivity** for real-world reporting.  
- Improved proficiency in **VBA scripting** and **dashboard protection techniques**.  
- Delivered a professional, client-ready dashboard that could support business decisions in real estate analytics.

---

## 🗂️ Repository Contents

