# 📊 Executive Sales Dashboard — Microsoft Excel

![Executive Sales Dashboard]([Executive_Sales_Dashboard.png](https://github.com/gloriatheanalyst/executive-dashboard-excel/blob/main/Executive%20Sales%20Dashboard.png))

---

## 📌 Project Overview

This project demonstrates how raw transactional sales data can be transformed into a **dynamic, interactive Executive Sales Dashboard** using Microsoft Excel. Built entirely without any BI software, the dashboard delivers the visual clarity and interactivity of tools like Power BI or Tableau using only Excel's native capabilities.

The dashboard is designed for **C-suite and management reporting**, enabling decision-makers to monitor KPIs, track year-over-year performance, and drill into sales behavior across products, people, regions, and payment channels — all from a single screen.

---

## 🧩 Business Problem

Sales teams and executives often struggle to extract timely, actionable insights from large transactional datasets scattered across spreadsheets. Without a consolidated view, identifying performance gaps, top-performing salespeople, or regional trends requires time-consuming manual analysis.

**This dashboard solves that by:**
- Centralizing all key sales metrics in one interactive view
- Enabling real-time filtering by year and store with slicers
- Visualizing trends and comparisons that would otherwise be buried in raw data

---

## 🎯 Objectives

- ✅ Build a fully interactive dashboard using only Microsoft Excel
- ✅ Create KPI cards tracking Revenue, Orders, Average Order Value (AOV), Discounts, and Returns with YoY % change
- ✅ Analyze performance across products, salespeople, regional managers, regions, and payment modes
- ✅ Design visuals that are executive-ready clean, professional, and immediately interpretable
- ✅ Implement dynamic filtering using Slicers and a Timeline control

---

## 🛠️ Tools & Techniques Used

| Tool / Feature | Purpose |
|---|---|
| **Pivot Tables** | Data aggregation and summarization |
| **Pivot Charts** | Dynamic, filter-responsive visualizations |
| **Slicers** | Interactive filtering by Store |
| **Timeline Slicer** | Interactive filtering by Year (2023–2025) |
| **Dynamic Scatter/Bubble Chart** | Product category revenue visualization |
| **Donut Chart** | Regional manager performance breakdown |
| **Lollipop Chart** | Salesperson performance ranking |
| **Line Chart** | Monthly sales trend visualization |
| **Horizontal Bar Chart** | Payment method comparison |
| **Sparklines** | Inline trend indicators in KPI cards |
| **Conditional Formatting** | ▲▼ YoY change indicators (green/red) |

---

## 📐 Dashboard Structure

### 1. 🔢 KPI Cards (Top Row)
Five headline metrics give executives an at-a-glance performance snapshot:

| Metric | Value | YoY Change |
|---|---|---|
| Total Revenue | 4.3M | ▲ 67.8% |
| Total Orders | 15,616 | ▲ 69.4% |
| Avg Order Value | 278 | ▼ 0.9% |
| Total Discounts | 347.9K | ▲ 68.0% |
| Total Returns | 372 | ▲ 72.2% |

Each card includes a **sparkline** showing the underlying trend and a **vs PY (Previous Year)** indicator.

---

### 2. 🛍️ Product Category Analysis (Center — Bubble Chart)
A radial bubble/scatter visualization maps **7 product categories** (Desk, Tablet, Laptop, Phone, Printer, Chair, Monitor) by revenue. The center node shows the **Retail channel share at 50.13%**, providing instant channel context alongside product performance.

---

### 3. 🏪 Revenue by Store (Bar Chart)
Vertical bar chart comparing revenue across 4 stores:
- **Store D** leads at **$1.2M**
- Stores A, C, and B follow closely at **$1.0M–$1.1M**
- Indicates strong performance consistency across locations

---

### 4. 👤 Salesperson Performance (Lollipop Chart)
Ranked view of 6 salespeople:
- **Bob** tops the leaderboard at **$790.2K**
- **Diana** ranks lowest at **$669.5K** — still a strong performer
- The narrow spread signals a well-balanced, high-performing team

---

### 5. 🌍 Regional Performance (Donut Chart)
Revenue breakdown across 5 regional managers (Cameron, Eric, Ryan, Sophie, Wendy):
- **North region** leads at **$960.0K**
- **East** follows at **$874.8K**
- Balanced regional distribution with no single dominant territory

---

### 6. 💳 Payment Method Analysis (Horizontal Bar Chart)
Revenue by payment channel:
- **Online** is the #1 channel at **$962K**
- **Cash** is a close second at **$942K**
- **Debit Card** trails at **$762K**
- Insight: Digital and in-person payments are nearly equal — suggesting a broad, omnichannel customer base

---

### 7. 📈 Sales Trend (Area Chart)
Monthly revenue trend across the full year (Jan–Dec):
- Reveals **seasonality patterns** and peak sales periods
- Smoothed area fill under the line adds visual depth while maintaining readability

---

### 8. 🗺️ Revenue by Region (Bar Chart)
Geographic revenue breakdown:
- **North** leads at **$960.0K**
- **South** trails at **$819.4K**
- Useful for identifying regional investment and growth opportunities

---

## 💡 Key Insights

1. **Revenue grew 67.8% YoY** — a strong signal of business growth or expanded data coverage across years
2. **Avg Order Value declined 0.9%** despite volume growth — suggesting more frequent but slightly smaller purchases; worth monitoring
3. **Returns rose 72.2% YoY** — growing at a rate exceeding revenue growth; warrants investigation into product quality or customer experience
4. **Tablet and Laptop are the top products** at ~$678K each — electronics dominate the product mix
5. **Online and Cash payments are nearly tied** — the business serves both digital-native and traditional customers equally
6. **Store performance is remarkably balanced** — no single store is dramatically outperforming, suggesting consistent operational standards
7. **North region leads consistently** across both Regional Performance and Revenue by Region charts

---

## 📂 Repository Structure

```
📁 executive-sales-dashboard/
├── 📊 Executive_Sales_Dashboard.xlsx   # Main Excel workbook
├── 🖼️ Executive_Sales_Dashboard.png    # Dashboard screenshot
└── 📄 README.md                        # Project documentation
```

---

## 🚀 How to Use

1. **Download** the `.xlsx` file
2. **Enable content** if prompted (required for slicers and pivot functionality)
3. Use the **Timeline slicer** (top right) to filter by year: 2023, 2024, or 2025
4. Use the **Store slicer** to filter by Store A, B, C, or D
5. All charts and KPI cards update **dynamically** based on your selection

---

## 👤 Author

**[Your Name]**
Data Analyst | Excel & Data Visualization

🔗 [LinkedIn Profile](#) | 🌐 [Portfolio](#) | 📧 [Email](#)

---

## 📃 License

This project is open for viewing and inspiration. Please credit the author if you use or adapt any part of this work.

---

*Built with 💚 in Microsoft Excel — no BI tools required.*
