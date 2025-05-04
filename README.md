# 📊 Amazon Sales Dashboard – Power BI Project

This project provides a comprehensive analysis of Amazon's sales data from 2022, focusing on trends in product performance, geographic demand, and shipping efficiency. Using over **128,975 records**, this Power BI dashboard offers deep insights to help optimize inventory, identify top-selling categories, and improve fulfillment strategies.

---

## 🎯 Objective

The objective of this dashboard is to evaluate key sales metrics across India by analyzing:
- Popular product **categories, sizes, and styles**
- **City- and state-level** demand patterns
- **Fulfillment performance** between Amazon and merchant sellers
- Revenue and quantity distributions across **channels and regions**

---

## 📁 Data Source

The dataset used for this report includes:
- 📄 **Amazon Sale Report.csv**
- [Download Amazon Sale Dataset (CSV)](https://drive.google.com/file/d/1ERd61P_1zFFQN_apLWaL7fQIp3UHppyP/view?usp=sharing)
- Contains order details, product attributes, fulfillment channels, ship cities, and states

---

## ⚙️ Power BI Features and Techniques

### 🧩 Data Modeling
- Linked multiple fields for city, state, and channel relationships
- Custom **hierarchies** for drill-downs (e.g., state → city)

### 🔄 Data Transformation (Power Query)
- Converted string dates to datetime format
- Removed duplicates and handled nulls
- Calculated derived columns like revenue per category
- Implemented filters for dynamic slicers

### 📐 Measures & Calculations
- Total Quantity, Sales, Avg. Sales per Order
- Grouped measures for size and shipping status comparisons

### 🔐 Security & UX
- Used **slicers** for Ship Status, State, Channel, Month
- Tooltips, buttons, and bookmarks for smoother navigation
- Custom visuals and themes for clarity

---

## 🔍 Analytics Questions Addressed

- Which cities and states have the highest number of orders?
- What are the top-selling product categories and sizes?
- How do Amazon vs Merchant fulfillment channels perform?
- What price ranges drive the most revenue?
- How does product size affect shipping success or cancellation?

---

## 📸 Screenshots

Below are key visualizations from the Power BI dashboard, showcasing dynamic insights from Amazon's 2022 sales data.

### 🧠 Executive Summary & Dashboard Overview

<table>
  <tr>
    <td><img src="Screenshots/Amazon Sales Report Analysis.PNG" width="400"/></td>
    <td><img src="Screenshots/Executive Summary.PNG" width="400"/></td>
  </tr>
  <tr>
    <td align="center">Introduction</td>
    <td align="center">Executive Summary</td>
  </tr>
</table>

---

### 📊 Dashboard & Ship Status Insights

<table>
  <tr>
    <td><img src="Screenshots/Dashboard Overview.PNG" width="400"/></td>
    <td><img src="Screenshots/Product Size vs Ship Status.PNG" width="400"/></td>
  </tr>
  <tr>
    <td align="center">Main Dashboard</td>
    <td align="center">Size vs Ship Status</td>
  </tr>
</table>

---

### 🛒 Category Analysis & Quick Metric View

<table>
  <tr>
    <td><img src="Screenshots/State vs Category Distribution.PNG" width="400"/></td>
    <td><img src="Screenshots/Tooltip Card for Quick Metrics.PNG" width="400"/></td>
  </tr>
  <tr>
    <td align="center">Category Distribution</td>
    <td align="center">Tooltip View</td>
  </tr>
</table>

---

### 🌍 Regional Sales by Category

<table>
  <tr>
    <td><img src="Screenshots/state vs catoget.PNG" width="400"/></td>
  </tr>
  <tr>
    <td align="center">State vs Category Sales</td>
  </tr>
</table>

---

## 💡 Key Insights

- **Bengaluru**, **Hyderabad**, and **Mumbai** dominate in total orders
- **Sets** and **Kurtas** are the highest-selling categories
- Sizes **M, L, XL** are most in demand
- **Amazon's own fulfillment** is faster and more successful than merchant delivery
- Products priced ₹449–₹788 account for majority of orders
- **Telangana** and **Uttar Pradesh** top the state-wise sales charts

---

## 🗂️ Project Folder Structure

amazon-sales-dashboard/
├── data/
│ └── Amazon Sale Report.csv
├── screenshots/
│ ├── 01_introduction.png
│ ├── 02_executive_summary.png
│ ├── 03_dashboard_overview.png
│ ├── 04_size_vs_status.png
│ ├── 05_category_summary.png
│ ├── 06_sales_table.png
│ ├── 07_tooltip_card.png
│ └── 08_state_category_distribution.png
├── README.md
└── .gitignore



---

## 🙌 Acknowledgments

This project was developed by **Ashish Pandya** as part of the final dashboarding assignment for the Artificial Intelligence with Data Analytics (AIDA) program at **Saskatchewan Polytechnic, Regina**.  
Special thanks to my mentors and classmates who provided feedback during dashboard development.

---

## 📬 Author

**Ashish Pandya**  
📘 AIDA Program | Saskatchewan Polytechnic  
📍 Regina, SK, Canada  
📧 Email: [drashishpandya@example.com]  
🔗 GitHub: [github.com/Ashishpandya-AI]

---

## 🛡 License

This repository is intended for academic and educational purposes. Attribution is appreciated if reused.

