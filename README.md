# 📊 Multi-National Company Sales Report — Power BI, Tableau & Google Looker Studio

A cross-platform data visualization project that builds the same sales dashboard in three industry-leading BI tools — Power BI, Tableau, and Google Looker Studio — analyzing $55.39M in sales and $31.59M in profit across 34 countries, 4 channels, and 6 product categories (2016–2019).

---

## 📌 Project Overview

This project demonstrates the ability to work across multiple BI platforms by replicating a comprehensive sales dashboard in **Power BI**, **Tableau**, and **Google Looker Studio** using the same underlying dataset. The dashboard tracks sales performance, profit distribution, channel effectiveness, and regional trends for a multinational electronics company — giving hiring managers a direct comparison of skills across all three major tools.

---

## 📁 Repository Structure

```
├── company_data.xlsx                          # Raw sales dataset (15,000 rows)
├── Sales_Report.pbix                          # Power BI dashboard file
├── Sales_Report_in_MS_Power_BI_.pdf           # Power BI dashboard screenshot
├── Sales_Report__in_Tableau_.pdf              # Tableau dashboard screenshot
└── Devices_Sales_Report__in_Google_Data_Studio_.pdf  # Looker Studio dashboard screenshot
```

---

## 🗄️ Dataset

**15,000 transactions × 17 columns | June 2016 – June 2019**

| Field | Description |
|---|---|
| `Order ID` | Unique order identifier |
| `Order Date` | Transaction date (2016–2019) |
| `Product Name` | Product name (1,638 distinct products) |
| `Product Category` | Category (Computers, Cameras, TV & Video, Cell phones, Audio, Music & Movies) |
| `Product Sub Category` | Sub-category detail |
| `Manufacturer` | 10 manufacturers (Fabrikam, Contoso, Adventure Works, etc.) |
| `Channel` | Sales channel (Store, Online, Reseller, Catalog) |
| `Promotion Name` | Promotion applied to the order |
| `Region` | Region (North America, Europe, Asia) |
| `Country` | Country (34 countries) |
| `City` | City of transaction |
| `Unit Cost` | Cost per unit |
| `Price` | Selling price per unit |
| `Order Qty` | Quantity ordered |
| `Cost of Sales` | Total cost |
| `Sales` | Total revenue |
| `Profit` | Revenue minus cost |

---

## 📊 Dashboard Features

All three dashboards share the same KPIs and visualizations:

### 🔢 KPI Cards
| Metric | Value |
|---|---|
| Total Sales | **$55.39M** |
| Total Profit | **$31.59M** |
| Average Sales | **$3.69K** |
| Average Profit | **$2.11K** |
| Number of Distinct Products | **1,638** |

### 📈 Visualizations Built
- **Sales & Profit by Month and Channel** — line/area chart tracking trends from 2016 to 2019 across Store, Online, Reseller, and Catalog channels
- **Profit by Channel** — donut/pie chart showing channel profit share
- **Sales by Product Category** — horizontal bar chart ranking 6 categories by revenue
- **Sales by Manufacturer** — matrix/bar chart comparing 10 manufacturers over time
- **Sales by Country and Region** — geographic map and bar chart across 34 countries in 3 regions
- **Interactive Filters** — slicers for Channel, Region, and Order Date range

---

## 🛠️ Part 1 — Power BI Dashboard

**File:** `Sales_Report.pbix`

- Built using **Power BI Desktop** with DAX measures for Total Sales, Total Profit, Average Sales, and Average Profit
- Used **donut chart** for profit by channel, **bar chart** for product categories, **line chart** for monthly trends, and **clustered bar** for country-level sales
- Added interactive **date range slicer** (02/06/2016 – 02/06/2019) and **region filter**
- Color scheme: dark background with blue/teal channel encoding

---

## 🛠️ Part 2 — Tableau Dashboard

**File:** `Sales_Report__in_Tableau_.pdf`

- Rebuilt the same dashboard in **Tableau Desktop**
- Used **area chart** for profit over time by channel, **horizontal bar** for category sales, **manufacturer heat matrix** showing sales trends per year, and **region breakdown** for North America, Europe, and Asia
- Added **channel** and **region** filter dropdowns for interactive drill-down
- Color scheme: clean white background with multi-color channel encoding

---

## 🛠️ Part 3 — Google Looker Studio Dashboard

**File:** `Devices_Sales_Report__in_Google_Data_Studio_.pdf`

- Rebuilt in **Google Looker Studio** (formerly Data Studio)
- Includes **KPI scorecards**, **donut chart** for channel share, **multi-series line chart** for quarterly trends (T2 2016 – T2 2019), **horizontal bar** for category sales, and an interactive **geographic map** showing profit by location worldwide
- Added **Channel** and **Region** dropdown filter controls
- Color scheme: yellow/orange branded theme with map overlay

---

## 💡 Key Findings

| Metric | Value |
|---|---|
| Total Sales | **$55.39M** |
| Total Profit | **$31.59M** (57.2% profit margin) |
| Top Channel by Profit | **Store — $18.05M (57.14%)** |
| Top Product Category | **Computers — $21.31M** |
| Top Manufacturer | **Fabrikam, Inc. — $12.05M** |
| Largest Region | **North America — 8,869 orders** |
| Countries Covered | **34 countries across 3 regions** |

- **Store channel** dominates with 57.14% of total profit — physical retail drives the most revenue
- **Computers** is the highest-grossing category at $21.31M, nearly double Cameras ($17.05M)
- **North America** accounts for the majority of orders (59%), followed by Europe (20.5%) and Asia (20.3%)
- **Fabrikam, Inc.** leads manufacturer sales at $12.05M, followed by Contoso ($10M) and Adventure Works ($7.47M)
- **Catalog channel** contributes the least profit at $2.9M (9.17%) — a potential optimization target

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — DAX measures, slicers, donut/bar/line charts, geographic visuals
- **Tableau Desktop** — calculated fields, filters, area charts, manufacturer matrix
- **Google Looker Studio** — scorecards, geographic maps, time series, dropdown controls
- **Microsoft Excel** — raw data source (.xlsx)
- **Techniques:** KPI cards, interactive filtering, cross-platform dashboard replication, time series analysis, geographic visualization, channel and category segmentation

---

## 🚀 Getting Started

### Power BI
1. Open `Sales_Report.pbix` in **Power BI Desktop**
2. Update the data source path to `company_data.xlsx` if prompted
3. Refresh data and interact with slicers

### Tableau
1. Connect `company_data.xlsx` as a data source in **Tableau Desktop**
2. Recreate the views following the layout in `Sales_Report__in_Tableau_.pdf`

### Google Looker Studio
1. Upload `company_data.xlsx` to Google Sheets
2. Connect as a data source in **Google Looker Studio**
3. Recreate the layout following `Devices_Sales_Report__in_Google_Data_Studio_.pdf`

> Power BI requires **Power BI Desktop** (free). Tableau requires **Tableau Desktop** or **Tableau Public** (free). Looker Studio is free via Google account.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
