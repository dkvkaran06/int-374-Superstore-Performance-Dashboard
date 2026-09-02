<div align="center">

<h1>
  🛒 Superstore Performance Dashboard
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Data%20Analytics-4A90E2?style=for-the-badge&logo=databricks&logoColor=white" alt="Data Analytics"/>
  <img src="https://img.shields.io/badge/Business%20Intelligence-FF6F61?style=for-the-badge&logo=tableau&logoColor=white" alt="Business Intelligence"/>
</p>

<p align="center">
  <strong>A comprehensive, interactive business intelligence dashboard built with advanced Power BI techniques,<br>
  delivering deep insights into retail superstore performance metrics.</strong>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-dashboard-insights">Insights</a> •
  <a href="#-dataset">Dataset</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-project-structure">Project Structure</a>
</p>

---

</div>

## 📊 Overview

The **INT-374 Superstore Performance Dashboard** is a data-driven analytics solution designed to transform raw retail transactional data into actionable business intelligence. This project leverages the full power of **Microsoft Power BI** to create an interactive, visually compelling dashboard that empowers stakeholders to make informed decisions at a glance.

Built on the classic **Sample Superstore Dataset**, the dashboard covers four years of retail operations across multiple product categories, customer segments, and geographic regions — turning thousands of data rows into clear, compelling visual narratives.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 📈 **Sales Trend Analysis** | Year-over-year and month-over-month revenue tracking with dynamic time intelligence |
| 💰 **Profit & Margin Insights** | Deep-dive into profitability by category, sub-category, and region |
| 🗺️ **Geographic Performance** | Interactive maps visualizing sales and profit distribution across states and cities |
| 👥 **Customer Segmentation** | Performance breakdown across Consumer, Corporate, and Home Office segments |
| 📦 **Product Analytics** | Best and worst performing products with contribution analysis |
| 🚚 **Shipping Mode Analysis** | Delivery efficiency and shipping cost impact on profitability |
| 🎯 **KPI Cards** | Real-time Key Performance Indicator snapshots for executive-level reporting |
| 🔄 **Dynamic Slicers** | Cross-filtering capabilities for interactive, drill-down data exploration |

---

## 📉 Dashboard Insights

The dashboard is structured around four core analytical views:

### 1. 🏠 Executive Summary
A high-level overview featuring KPI cards for **Total Sales**, **Total Profit**, **Order Count**, and **Average Discount**. Sparkline trends and period-over-period comparisons give an instant health check of the business.

### 2. 📦 Product & Category Performance
Bar charts and treemaps reveal which product categories — **Furniture**, **Office Supplies**, and **Technology** — drive the most revenue and which sub-categories erode margins (e.g., Tables & Bookcases).

### 3. 🌍 Regional & Geographic View
A **filled map visual** breaks down performance by US state, making it easy to identify high-performing regions (e.g., California, New York) versus underperforming markets.

### 4. 👤 Customer & Segment Deep Dive
Scatter plots and segment comparisons surface the most valuable customer cohorts and expose which segments yield the highest lifetime value.

---

## 🗂️ Dataset

The project uses the **Sample Superstore Subset** dataset — a widely-used benchmark dataset in the BI community.

| Attribute | Details |
|---|---|
| **Source** | Sample Superstore (Tableau/Excel) |
| **Records** | ~10,000 orders |
| **Time Range** | 4 Years of transactional data |
| **Key Columns** | Order ID, Order Date, Ship Mode, Customer Segment, Product Category, Sales, Quantity, Discount, Profit, Region, State |
| **Format** | `.xlsx` (Excel Workbook) |

> 📁 The raw dataset is included in this repository as `sample-superstore-subset-excel dashboard dat...`

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Microsoft%20Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" height="25"/>
  &nbsp;
  <img src="https://img.shields.io/badge/DAX%20(Data%20Analysis%20Expressions)-0078D4?style=flat-square&logo=microsoft&logoColor=white" height="25"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Power%20Query%20(M%20Language)-217346?style=flat-square&logo=microsoftexcel&logoColor=white" height="25"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" height="25"/>
</p>

### Advanced Power BI Concepts Used
- **DAX Measures** — Custom calculated measures for KPIs, YoY growth, running totals, and dynamic rankings
- **Power Query (M Language)** — Data cleansing, transformation pipelines, and column profiling
- **Time Intelligence Functions** — `SAMEPERIODLASTYEAR`, `TOTALYTD`, `DATEADD` for temporal analysis
- **Bookmarks & Drill-throughs** — Navigation buttons and drill-through pages for contextual analysis
- **Conditional Formatting** — Heat maps and data bars to highlight outliers and top performers
- **Report-Level Filters & Slicers** — Dynamic cross-filtering across all visuals

---

## 🚀 Getting Started

### Prerequisites

- **Microsoft Power BI Desktop** (Free) — [Download here](https://powerbi.microsoft.com/en-us/desktop/)
- **Microsoft Excel** (for the raw dataset)

### Steps to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/dkvkaran06/int-374-Superstore-Performance-Dashboard.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd int-374-Superstore-Performance-Dashboard
   ```

3. **Open the Power BI report**
   - Launch **Power BI Desktop**
   - Click `File` → `Open` → Select the `.pbix` file from the cloned folder

4. **Verify data source**
   - Go to `Transform Data` → `Data Source Settings`
   - Update the Excel file path to match your local directory if prompted

5. **Explore the Dashboard**
   - Use the slicers (Year, Region, Segment, Category) to filter data interactively
   - Click on any visual to cross-filter related charts
   - Use drill-through on product/region visuals for deeper insights

---

## 📁 Project Structure

```
📦 int-374-Superstore-Performance-Dashboard
├── 📊 Dashboard int 374 Dev Karan 12321910 KM004.pbix   # Main Power BI Report
├── 📂 sample-superstore-subset-excel dashboard dat.xlsx  # Raw Dataset (Excel)
└── 📄 README.md                                          # Project Documentation
```

---

## 📸 Dashboard Preview

> **Note:** Open the `.pbix` file in Power BI Desktop to experience the full interactive dashboard with slicers, drill-throughs, and live cross-filtering.

---

## 🎓 Learning Outcomes

Working through this project builds proficiency in:

- ✅ Connecting and transforming real-world retail data with **Power Query**
- ✅ Writing efficient **DAX** measures for business KPIs
- ✅ Designing intuitive, executive-ready report layouts
- ✅ Applying **Time Intelligence** to reveal trends over time
- ✅ Implementing interactive navigation using **Bookmarks** and **Buttons**
- ✅ Storytelling with data through well-chosen chart types

---

## 👨‍💻 Author

<table>
  <tr>
    <td align="center">
      <strong>Dev Karan</strong><br/>
      <sub>Student ID: 12321910 | KM004</sub><br/>
      <sub>INT-374 Business Intelligence & Analytics</sub><br/><br/>
      <a href="https://github.com/dkvkaran06">
        <img src="https://img.shields.io/badge/GitHub-dkvkaran06-181717?style=flat-square&logo=github" />
      </a>
    </td>
  </tr>
</table>

---

## 📄 License

This project is created for academic purposes as part of the **INT-374** coursework.  
Feel free to explore, fork, and build upon it for your own learning journey.

---

<div align="center">

⭐ **If you found this project helpful, please consider giving it a star!** ⭐

<br/>

*Made with ❤️ and the power of data*

</div>
