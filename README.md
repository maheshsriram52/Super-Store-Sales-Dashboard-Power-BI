<div align="center">

# 🛒 **SUPER STORE SALES DASHBOARD**
### 📊 End-to-End Business Intelligence Project | Power BI

<br/>

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-8A2BE2?style=for-the-badge&logo=tableau&logoColor=white)

<br/>

> 🚀 *Transforming raw retail transactional data into a powerful, interactive executive dashboard — driving smarter decisions across sales, profit, and operations.*

<br/>

![Dashboard Preview](https://github.com/maheshsriram52/Super-Store-Sales-Dashboard-Power-BI/blob/main/Super%20Store%20Sales%20Dashboard.png)

</div>

---

## 📌 **PROJECT OVERVIEW**

This project presents a fully interactive **Super Store Sales Performance Dashboard** developed using **Microsoft Power BI**. It covers **2 years of retail sales data (2019–2020)** across multiple U.S. regions, converting over **22,000 raw order records** into a clean, executive-ready business intelligence solution.

The dashboard enables business leaders, sales managers, and analysts to:
- 📈 Monitor **real-time KPIs** — Sales, Profit, Orders, and Delivery Performance
- 🗺️ Drill into **regional and state-level** performance using interactive maps
- 🔎 Identify **high-growth product categories** and underperforming segments
- 📅 Compare **Year-over-Year trends** for strategic forecasting and planning

---

## 🎯 **BUSINESS OBJECTIVES**

| # | Objective |
|---|-----------|
| 1️⃣ | Track and visualize overall **Sales, Profit, and Order Volume** through dynamic KPI cards |
| 2️⃣ | Identify **top-performing product categories and sub-categories** to guide inventory decisions |
| 3️⃣ | Analyze **regional and state-level performance** to uncover geographic growth opportunities |
| 4️⃣ | Understand **customer segment contribution** (Consumer, Corporate, Home Office) to revenue |
| 5️⃣ | Evaluate **shipping mode efficiency** and its impact on delivery timelines |
| 6️⃣ | Compare **monthly sales and profit trends** across 2019 vs 2020 for YoY analysis |
| 7️⃣ | Decode **payment mode preferences** to inform digital adoption strategies |

---

## 🗂️ **DATASET INFORMATION**

| 📋 Attribute | 📝 Details |
|-------------|-----------|
| **Domain** | 🏬 Retail / E-Commerce |
| **Time Period** | 📅 January 2019 – December 2020 |
| **Total Records** | 📦 ~22,000 Orders |
| **Geography** | 🗺️ United States (Multi-Region) |
| **Key Fields** | Order Date, Ship Mode, Segment, Category, Sub-Category, Sales, Profit, Region, State, Payment Mode |
| **Source Type** | Structured CSV / Excel |

---

## 🛠️ **TOOLS & TECHNOLOGIES**

| 🔧 Tool | 💡 Purpose |
|--------|-----------|
| ![Power BI](https://img.shields.io/badge/-Power%20BI%20Desktop-F2C811?logo=powerbi&logoColor=black&style=flat-square) | Dashboard design, report publishing, and interactive visualization |
| ![Power Query](https://img.shields.io/badge/-Power%20Query%20(M)-217346?logo=microsoftexcel&logoColor=white&style=flat-square) | Data ingestion, cleaning, transformation, and feature engineering |
| ![DAX](https://img.shields.io/badge/-DAX-0078D4?logo=microsoftazure&logoColor=white&style=flat-square) | Custom KPI measures, calculated columns, and time intelligence functions |
| ![Bing Maps](https://img.shields.io/badge/-Bing%20Maps-00897B?logo=microsoft&logoColor=white&style=flat-square) | Geospatial visualization of sales and profit performance by state |

---

## ⚙️ **METHODOLOGY & WORKFLOW**

```text
📥 Data Ingestion  ──►  🧹 Data Cleaning  ──►  🔗 Data Modelling
                                                        │
                                                        ▼
📤 Dashboard Publishing  ◄──  🎨 Visual Design  ◄──  📐 DAX Measures
```

### 🔷 **Step 1 — Data Ingestion**
Imported raw retail CSV data into Power BI Desktop. Performed initial data profiling to assess completeness, column distributions, and quality issues.

### 🔷 **Step 2 — Data Cleaning & Transformation**
Leveraged **Power Query (M Language)** to:
- Remove duplicates and handle null/missing values
- Standardize data types (dates, decimals, text)
- Engineer new date features — **Month Name, Month Number, Year** — for time-based analysis

### 🔷 **Step 3 — Data Modelling**
Built a clean **Star Schema** by establishing relationships between dimension tables (Products, Customers, Dates, Geography) and the central fact table (Orders), enabling efficient cross-filtering and slicing.

### 🔷 **Step 4 — DAX Measures**
Developed custom business measures using **DAX**, including:
- `Total Sales`, `Total Profit`, `Profit Margin %`
- `Total Orders`, `Average Delivery Days`
- `YoY Sales Growth`, `MoM Profit Change`

### 🔷 **Step 5 — Visualization Design**
Crafted an intuitive **dark-themed executive dashboard** using KPI cards, line charts, bar charts, donut charts, and a Bing Map — all designed for rapid insight consumption by non-technical stakeholders.

### 🔷 **Step 6 — Interactivity & Slicers**
Implemented dynamic **Region slicers** (Central, East, South, West) and **Year toggles** (2019 / 2020) that cross-filter all visuals simultaneously for drill-down analysis.

---

## 📊 **DASHBOARD VISUALS**

| 🖼️ Visual | 📌 Chart Type | 📝 Description |
|----------|-------------|---------------|
| **KPI Cards** | Card Visuals | Total Sales (1.57M) · Orders (22K) · Profit (175.26K) · Avg Delivery (9.57 days) |
| **Sales by Month** | Line Chart | Monthly sales trend comparison — 2019 🔵 vs 2020 🔷 |
| **Profit by Month** | Line Chart | Monthly profit trend comparison — 2019 🔵 vs 2020 🔷 |
| **Sales by Category** | Horizontal Bar | Office Supplies 0.64M · Technology 0.47M · Furniture 0.45M |
| **Sales by Sub-Category** | Horizontal Bar | Top items — Phones 0.20M · Chairs 0.18M · Binders 0.17M |
| **Sales by Ship Mode** | Horizontal Bar | Standard Class 0.33M · Second Class 0.11M · First Class 0.08M · Same Day 0.03M |
| **Sales by Segment** | Donut Chart | Consumer 48% · Corporate 33% · Home Office 19% |
| **Sales by Payment Mode** | Donut Chart | COD 43% · Online 35% · Cards 22% |
| **Sales by Region** | Donut Chart | West 33% · East 29% · Central 22% · South 16% |
| **Sales & Profit by State** | Bing Map | Geospatial bubble map across all U.S. states |

---

## 🔍 **KEY INSIGHTS & FINDINGS**

> 💡 *Data-backed insights derived from dashboard analysis — ready to present in interviews or stakeholder reviews.*

- 🏆 **Office Supplies leads** all categories at **$0.64M** in revenue, outperforming Technology ($0.47M) and Furniture ($0.45M) — indicating strong B2B demand for consumables.

- 📱 **Phones ($0.20M) and Chairs ($0.18M)** are the top two sub-categories, collectively driving ~**$0.38M** in sales — prime candidates for promotional investment.

- 🚚 **Standard Class shipping dominates at $0.33M** (~61% of all shipments), revealing strong price sensitivity among customers — premium shipping modes remain underutilized.

- 👥 The **Consumer segment drives 48%** of total revenue — nearly **1 in 2 dollars** comes from individual buyers, making it the most critical segment for retention strategies.

- 💳 **COD is the #1 payment method at 43%**, signaling a trust gap with digital payments — an opportunity to incentivize card and online payment adoption through discounts or loyalty programs.

- 🌍 The **West region leads at 33%** of total sales, while the **South region at 16%** is the lowest — a clear signal for targeted regional marketing campaigns.

- 📅 **2020 outperformed 2019** across nearly every month, with a strong **Q4 sales spike** in both years — indicating predictable seasonal demand that can be leveraged for inventory planning.

- ⏱️ An **average delivery time of 9.57 days** is above industry benchmarks — reducing this could significantly improve customer satisfaction and repeat purchase rates.

---

## 💼 **BUSINESS VALUE DEMONSTRATED**

```
✅  Unified 22K+ orders into a single executive-ready dashboard
✅  Reduced reporting time with automated, interactive visuals
✅  Enabled regional drill-down for territory-based business reviews
✅  Surfaced $$ growth opportunities in underperforming regions
✅  Identified payment and shipping bottlenecks for operational improvement
✅  Delivered YoY comparison enabling accurate sales forecasting
✅  Made complex data accessible to non-technical decision-makers
```

---

## 🧠 **SKILLS DEMONSTRATED**

<div align="center">

`Power BI` &nbsp; `DAX` &nbsp; `Power Query` &nbsp; `M Language` &nbsp; `Data Modelling` &nbsp; `Star Schema`
`KPI Dashboard Design` &nbsp; `Data Visualization` &nbsp; `Business Intelligence` &nbsp; `Storytelling with Data`
`Geospatial Analysis` &nbsp; `Time Intelligence` &nbsp; `YoY Analysis` &nbsp; `Retail Analytics` &nbsp; `Executive Reporting`

</div>

---

## 📁 **PROJECT STRUCTURE**

```
📦 superstore-sales-dashboard/
│
├── 📊 SuperStore_Sales_Dashboard.pbix     # Power BI report file
├── 🖼️  SuperStore_Sales_Dashboard.pdf     # Dashboard preview (PDF export)
├── 📂 data/
│   └── 📄 superstore_sales.csv            # Raw source dataset
├── 📂 screenshots/
│   └── 🖼️  dashboard_preview.png          # Dashboard screenshot
└── 📝 README.md                           # Project documentation
```

---

## 🚀 **HOW TO RUN THIS PROJECT**

```bash
# Step 1 — Clone the repository
git clone (https://github.com/maheshsriram52/Super-Store-Sales-Dashboard-Power-BI)

# Step 2 — Navigate into the project folder
cd Super-Store-Sales-Dashboard-Power-BI
```

> 📥 **Step 3** — Open `SuperStore_Sales_Dashboard.pbix` in **Power BI Desktop**


> 🔗 **Step 4** — If prompted, reconnect the data source to `data/superstore_sales.csv`

> 🎛️ **Step 5** — Use the **Region slicers** (Central · East · South · West) and **Year filters** (2019 / 2020) to explore the dashboard interactively

---

## 📈 **FUTURE ENHANCEMENTS**

- [ ] 🔮 Integrate **sales forecasting** using Power BI's built-in AI analytics
- [ ] 🔔 Add **data alerts** for profit margin drops below threshold
- [ ] ☁️ Publish to **Power BI Service** for cloud-based sharing and scheduled refresh
- [ ] 📱 Optimize layout for **Power BI Mobile** responsive design
- [ ] 🤖 Incorporate **Q&A natural language** query panel for self-serve analytics

---

## 📬 **CONNECT WITH ME**

<div align="center">

| 👤 **Sriram Mahesh Babu** |
|---|
| 📧 [your.email@example.com](maheshsriram52@gmail.com) |
| 🔗 [LinkedIn]([https://linkedin.com/in/your-profile](https://www.linkedin.com/in/srirammaheshbabu)) |


</div>

---

<div align="center">

### ⭐ If you found this project useful, please consider giving it a star!

*📌 This project is part of my Data Analytics Portfolio — showcasing end-to-end BI development, data storytelling, and business insight generation using Power BI.*

<br/>

**Made with ❤️ and lots of ☕ by [Your Name]**

</div>
