# Retail Sales Performance Dashboard

## 📊 Project Overview

**Retail Sales Performance Dashboard** is an Excel-based business analytics project designed to analyze sales performance across regions, sales channels, customer types, product categories, individual products, and salespeople.

The workbook transforms raw order-level data into **PivotTables, detailed analysis views, and an interactive dashboard** to help stakeholders monitor revenue, sales volume, product performance, and channel effectiveness.

---

## 🎯 Business Objective

The main objective is to answer key business questions such as:

- What is the overall sales revenue and order volume?
- Which regions generate the highest revenue?
- Which sales channels perform best?
- Which product categories and products contribute the most revenue?
- How do new and returning customers compare?
- Which salespeople generate the highest revenue?
- How does revenue change month by month?
- Which products or categories may require additional business attention?

---

## 🗂️ Dataset

The workbook contains **2,000 unique orders** and **13 analytical fields**.

### Dataset Summary

| Metric | Value |
|---|---:|
| Orders | 2,000 |
| Total Quantity Sold | 7,552 |
| Total Revenue | 3,462,605.32 |
| Average Revenue per Order | 1,731.30 |
| Regions | 5 |
| Sales Channels | 4 |
| Customer Types | 2 |
| Product Categories | 6 |
| Products | 28 |
| Salespeople | 15 |
| Data Period | January–December 2026 |

### Data Fields

| Column | Description |
|---|---|
| `Order ID` | Unique identifier for each order |
| `Date` | Order date |
| `Region` | Geographic region |
| `Sales Channel` | Channel through which the order was generated |
| `Customer Type` | New or Returning customer |
| `Product Category` | Broad product classification |
| `Product` | Specific product sold |
| `Salesperson` | Salesperson responsible for the order |
| `Quantity` | Number of units sold |
| `Unit Price` | Price per unit before discount |
| `Discount` | Discount applied to the order |
| `Revenue` | Revenue generated from the order |
| `Month` | Month derived from the order date |

---

## 🧹 Data Preparation

The raw data was structured for analysis and dashboard reporting.

Key preparation activities include:

1. Validating order IDs and dates.
2. Converting dates into a proper date format.
3. Creating a month field for time-based analysis.
4. Checking numerical fields such as quantity, unit price, discount, and revenue.
5. Validating categorical dimensions such as region, channel, customer type, category, product, and salesperson.
6. Checking for missing values and inconsistent records.
7. Preparing the dataset for PivotTable-based analysis.

The supplied analytical data contains **no missing values across the 13 core fields**.

---

## 📈 Key KPIs

The workbook supports the following important business KPIs:

- **Total Revenue:** 3,462,605.32
- **Total Orders:** 2,000
- **Total Quantity Sold:** 7,552
- **Average Revenue per Order:** 1,731.30
- Revenue by Region
- Revenue by Sales Channel
- Revenue by Customer Type
- Revenue by Product Category
- Revenue by Product
- Revenue by Salesperson
- Monthly Revenue Trend

---

## 📊 Dashboard Analysis

### 1. Regional Sales Analysis

Compare revenue and order performance across:

- East
- West
- North
- South
- Central

This helps identify high-performing and underperforming geographic markets.

### 2. Sales Channel Analysis

The dataset contains four sales channels:

- Online
- Retail Store
- Corporate Sales
- Marketplace

Channel-level analysis helps evaluate where revenue is being generated and where sales efforts may need improvement.

### 3. Customer Analysis

Customers are divided into:

- New
- Returning

Comparing these segments can help evaluate customer retention and understand the contribution of repeat customers to revenue.

### 4. Product Category Analysis

The six product categories are:

- Accessories
- Storage
- Networking
- Computers
- Monitors
- Office Supplies

Category analysis identifies major revenue contributors and helps support product portfolio decisions.

### 5. Product-Level Analysis

The dashboard can drill down from category to individual products to identify:

- Best-selling products
- Highest-revenue products
- Low-performing products
- Product contribution within each category

### 6. Salesperson Performance

Revenue can be analyzed by salesperson to compare individual sales performance and identify top contributors.

### 7. Monthly Trend Analysis

The `Month` field enables month-wise analysis of revenue and quantity sold.

This supports:

- Monthly performance tracking
- Trend identification
- Peak-period analysis
- Sales planning

---

## 🔄 Workbook Structure

The Excel workbook contains four main sheets:

```text
Data
  ↓
Pivot Table
  ↓
Detail1
  ↓
Dashboard
```

### `Data`

Contains the core order-level dataset used for analysis.

### `Pivot Table`

Contains PivotTable-based summaries for dimensions such as region, product, category, sales channel, and overall KPIs.

### `Detail1`

Provides detailed records for selected PivotTable analysis, including product-level revenue details.

### `Dashboard`

Provides the visual business reporting layer for communicating sales performance.

---

## 📊 PivotTable Analysis

PivotTables are used to summarize large volumes of order data into business-friendly metrics.

Typical analyses include:

- Sum of Revenue
- Count of Orders
- Sum of Quantity
- Average Revenue
- Revenue by Region
- Revenue by Product
- Revenue by Product Category
- Revenue by Sales Channel

This approach allows users to dynamically filter and drill into the sales data.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- **PivotTables**
- **PivotCharts**
- **Excel Dashboard**
- **Data Cleaning & Transformation**
- **Business Intelligence / Data Visualization**

---

## 🔄 Project Workflow

```text
Raw Order Data
      ↓
Data Validation & Preparation
      ↓
Month / Analytical Fields
      ↓
PivotTable Analysis
      ↓
Detailed Drill-Down
      ↓
Interactive Dashboard
      ↓
Business Insights
```

---

## 💡 Business Insights

The dashboard can help management:

- Monitor total revenue and sales volume.
- Identify high-performing regions.
- Compare online, retail, corporate, and marketplace channels.
- Understand the contribution of new versus returning customers.
- Identify high-value product categories.
- Find top-performing individual products.
- Compare salesperson performance.
- Track monthly sales trends.
- Support sales planning and resource allocation.

---

## 📋 Business Analyst Skills Demonstrated

This project demonstrates skills relevant to **Business Analyst, Data Analyst, and BI Analyst** roles:

- Business problem identification
- KPI definition
- Data validation
- Data preparation
- Exploratory data analysis
- Sales performance analysis
- Customer segmentation
- Product analysis
- Regional analysis
- Channel performance analysis
- Trend analysis
- PivotTable analysis
- Dashboard development
- Data visualization
- Business reporting
- Performance monitoring
- Actionable insight generation
- Data-driven decision support

---

## 🚀 Future Enhancements

Potential improvements include:

- Adding month-over-month growth KPIs.
- Adding year-over-year comparisons when multiple years are available.
- Creating dynamic Top-N product analysis.
- Adding sales targets versus actual performance.
- Adding salesperson target achievement.
- Adding profit/margin analysis if cost data becomes available.
- Adding customer lifetime value analysis.
- Adding interactive slicers for region, category, channel, and customer type.
- Automating data refresh.
- Adding conditional formatting for underperforming areas.

---

## 📁 Project Files

Typical project structure:

```text
Retail-Sales-Dashboard/
│
├── Data.xlsx
└── README.md
```

The provided workbook includes:

```text
Data (2).xlsx
├── Detail1
├── Pivot Table
├── Dashboard
└── Data
```

---

## 👤 Project Role

**Role:** Business / Data Analytics Project

### Responsibilities

- Prepared and validated order-level sales data.
- Structured data for business analysis.
- Created PivotTable-based performance analysis.
- Developed revenue and sales KPIs.
- Analyzed regional, channel, customer, category, product, and salesperson performance.
- Created detailed drill-down analysis.
- Designed an Excel dashboard for management-oriented reporting.
- Translated sales data into actionable business insights.

---

## ⭐ Key Takeaway

**The Retail Sales Performance Dashboard converts 2,000 order records into an interactive Excel business intelligence solution for monitoring revenue, sales volume, customer segments, product performance, sales channels, regions, and salesperson effectiveness.**
