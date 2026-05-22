# 📊 AdventureWorks Sales Dashboard

A Power BI dashboard built on the AdventureWorks dataset, covering end-to-end sales and revenue analysis — from overall KPIs down to individual product and customer performance.

---

## 🗂 Project Overview

This dashboard gives a full picture of business performance across orders, revenue, profit, cost, and returns. It's built for quick decision-making with interactive filters, drill-downs, and geographic breakdowns.

**4 report pages:**
- Executive Summary (KPIs and trends)
- Geographic View (returns by region/country)
- Product Performance (subcategory & product-level analysis)
- Customer Details (per-customer breakdown)

---

## 📸 Dashboard Screenshots

### Page 1 — Executive Summary
- <a href="https://github.com/ummehumaera1-droid/Coffee_Shop_Sales_Performance_Dashboard/blob/main/Coffee_Shop_Sales.xlsx">Executive Summary</a>

### Page 2 — Geographic View
![Geographic View](screenshots/map-view.png)

### Page 3 — Product Performance
![Product Performance](screenshots/product-performance.png)

### Page 4 — Customer Details
![Customer Details](screenshots/customer-details.png)

---

## 💡 Key Insights

| Metric | Value |
|---|---|
| Total Orders | 17.42K |
| Total Revenue | $10.68M |
| Total Profit | $4.45M |
| Total Cost | $6.23M |
| Total Returns | 1.81K |
| Quantity Sold | 29.40K |
| Avg Revenue per Customer | $588.50 |
| Avg Profit per Customer | $245.26 |
| Return Rate | 6.22% |

**Top Findings:**
- Road Bikes is the highest revenue subcategory at **$6.9M**, followed by Mountain Bikes at **$3.3M**
- Professionals generate the most profit at **$1.4M** among all occupations
- Revenue is nearly evenly split between male (50.29%) and female (49.06%) customers
- Monthly orders, revenue, and profit are all running below target (goals missed by 30–45%)
- USA and Europe (UK, France, Germany) are the primary markets by return volume

---

## 🗃 Data Source

| Detail | Info |
|---|---|
| **Dataset** | AdventureWorks (Microsoft sample dataset) |
| **File Format** | Power BI `.pbix` |
| **Key Tables** | Sales, Products, Customers, Returns, Calendar |
| **Metrics** | Revenue, Profit, Cost, Orders, Returns, Quantity Sold |

---

## 🚀 How to Open & Use

### Requirements
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) — free, Windows only
- File: `Assigmnent-1.pbix`

### Steps

1. Install **Power BI Desktop**
2. Download or clone this repository
3. Open `Assigmnent-1.pbix` in Power BI Desktop
4. Use the **filter panel** to slice by date, region, or category
5. Click on any chart to cross-filter other visuals on the page
6. Use the **left sidebar icons** to navigate between the 4 report pages

### Report Pages

| Icon | Page | What It Shows |
|---|---|---|
| 🏠 | Executive Summary | KPIs, revenue & profit trends, gender split, subcategory revenue |
| 📍 | Geographic View | Returns plotted on world map by region/country |
| 📦 | Product Performance | Product table + subcategory-wise profit chart |
| 👥 | Customer Details | Per-customer revenue, profit, cost, and order data |

---

## 🛠 Built With

- [Power BI Desktop](https://powerbi.microsoft.com/)
- DAX for calculated measures (return rate, averages, comparisons)
- Power Query (M) for data transformation
- Bing Maps visual for geographic analysis

---

## 📁 Repository Structure

```
├── Assigmnent-1.pbix        # Power BI report file
├── README.md                # This file
└── screenshots/
    ├── dashboard-overview.png
    ├── map-view.png
    ├── product-performance.png
    └── customer-details.png
```

---

## 👤 Author

**Your Name**
GitHub: [@your-username](https://github.com/your-username)

---

*Assignment 1 | Power BI | AdventureWorks Sales Analysis*
