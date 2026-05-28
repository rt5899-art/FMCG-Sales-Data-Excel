# FMCG Sales Data Analytics Dashboard

An interactive Excel-based analytics solution designed to track, analyze, and visualize Fast-Moving Consumer Goods (FMCG) sales performance. This dashboard processes raw transactional metrics into actionable insights regarding revenue velocity, brand performance, regional distribution networks, and key account management.

## 🚀 Key Features

* **Dynamic Performance Cockpit:** Centralized interactive surface offering rapid cross-filtering of global FMCG commercial metrics.
* **Granular Product & Brand Diagnostics:** In-depth evaluation of SKU performance, product categories, and brand margins.
* **Supply & Distribution Insights:** Analysis of fulfillment pipelines, channel performance (Modern Trade, Traditional Trade, E-commerce), and order volume frequencies.
* **Interactive Slicers & Timelines:** Automated parameters enabling frictionless data slicing across multi-tier regional hierarchies and fiscal timelines.

---

## 📊 Dashboard Architecture

The workbook uses an optimized data-to-dashboard pipeline separating data storage from presentation logic:

### 1. Interactive Dashboard (Front-End)
The core reporting surface utilized for business reviews and executive summaries:
* **Core KPI Cards:** High-level metrics tracking **Total Revenue**, **Gross Margins**, **Total Volume Sold (Units)**, and **Average Order Value (AOV)**.
* **Trend Analysis:** Line and area charts mapping sales growth, seasonality patterns, and rolling monthly performance.
* **Categorical Matrices:** Bar/Column charts sorting distribution concentration by **Product Category** (e.g., Food & Beverages, Personal Care, Household Items) and individual **Brands**.
* **Regional & Channel Splits:** Donut/Pie or Map visuals breakdown sales contribution by sales regions, target demographics, and retail outlets.

### 2. Analytical Pivot Engine (Middle Layer)
* Contains organized **Pivot Tables** and **Pivot Charts** sourcing data directly from the cleaned transactions.
* Houses explicit calculated fields defining corporate margins, revenue per volume indices, and target completion percentages.

### 3. Ingestion & Structured Tables (Back-End)
* **Fact Sales Data:** Organized, clean flat-file rows compiling Order Dates, SKU Codes, Quantities, Unit Prices, Discounts, Subtotals, and Retailer profiles.
* **Dimension Master Data:** Supportive lookups map SKU codes to categories and establish regional territory hierarchies.

---

## 🧮 Sample Metrics & Calculations

The sheet utilizes robust spreadsheet calculations to standardize performance indications:

* **Gross Revenue:**
  $$\text{Gross Revenue} = \text{Units Sold} \times \text{Unit Selling Price}$$
  
* **Net Profit Margin (%):**
  $$\text{Net Margin \%} = \left( \frac{\text{Net Revenue} - \text{Cost of Goods Sold (COGS)}}{\text{Net Revenue}} \right) \times 100$$

* **Volume Velocity (Run-Rate):** Average units cleared across distribution centers per operational cycle.

---

## 🛠️ Usage and Instructions

To explore or extend this spreadsheet locally:

1. **Prerequisites:** Ensure you have **Microsoft Excel 2016 or newer** (with Power Pivot enabled for optimal feature compatibility).
2. **Download or Clone:**
   ```bash
   git clone [https://github.com/rt5899-art/FMCG-Sales-Data-Excel.git](https://github.com/rt5899-art/FMCG-Sales-Data-Excel.git)# FMCG-Sales-Data-Excel
