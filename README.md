# 🛒 Sales Dashboard — Electronic Sales

An Excel-based sales analytics dashboard built from **20,000 electronic sales transactions** (2023–2024), covering product performance, loyalty scoring, add-on purchases, sales trends, and revenue breakdowns by product type. The dashboard features interactive slicers, pie charts, bar charts, and trend lines.

---

## 🛒 Dashboard Overview

### 💰 Key Metrics
- **Total Sales Revenue**: ₹52,48,102.57
- **Total Quantity Sold**: ₹1,999.00
- **Average Unit Price**: ₹476.49

---


## 🗂️ Workbook Structure

| Sheet | Purpose |
|-------|---------|
| `Electronic_sales` | Raw transaction dataset (20,000 records) |
| `Dashboard` | Interactive sales dashboard |
| `Sheet2–Sheet8`, `Sheet13` | Supporting pivot/calculation sheets |

---

## 📊 Dashboard KPIs

| Metric | Value |
|--------|-------|
| 💰 Total Price (Revenue) | ₹ 52,48,102.57 (dashboard view) |
| 📦 Quantity | Displayed via KPI card |
| 💵 Average Unit Price | ₹ 476.49 (dashboard view) |

> Full dataset total revenue: **₹ 6,36,02,668** across 20,000 records.

---

## 📈 Dashboard Sections

### 1. 🏷️ Total Price by Product Type (Bar Chart)
| Product Type | Total Revenue |
|--------------|--------------|
| Smartphone | ₹ 2,15,16,754 |
| Smartwatch | ₹ 1,40,36,273 |
| Laptop | ₹ 1,22,96,239 |
| Tablet | ₹ 1,17,12,000 |
| Headphones | ₹ 40,41,400 |

---

### 2. 🥧 Total Sales Distribution (Pie Chart)
Breakdown of total sales share by product type — Smartphone leads at **~29%**, followed by Smartwatch, Laptop, and Tablet each in the **8%–13%** range.

---

### 3. 📉 Sales Trend of Top 3 Products (Line Chart)
Year-wise trend for Laptop, Smartphone, Smartwatch, and Tablet:
- **2023 peaks:** Laptop ₹6.77L, Smartphone ₹13.41L, Smartwatch ₹13.88L
- **2024 values:** Tablet ₹1.57L, Smartwatch ₹3.89L, Smartphone ₹4.89L

---

### 4. 🏆 Top 5 Products by Loyalty Score (Bar Chart)
Displays combined Count of Total Price and Loyalty Score for each product category — Laptop, Smartphone, Smartwatch, and Tablet.

---

### 5. 🧩 Add-ons Purchased Distribution
| Add-on | Count |
|--------|-------|
| Impulse Item | 5,098 |
| Accessory | 5,037 |
| Extended Warranty | 4,997 |

---

## 🔍 Filter Panel (Slicers)

| Slicer | Options |
|--------|---------|
| **Years (Purchase Date)** | 2023, 2024 |
| **Product Type** | Laptop, Smartphone, Smartwatch, Tablet |
| **Add-ons Purchased** | Accessory, Extended Warranty, Impulse Item |

---

## 🗃️ Dataset — Column Reference

The `Electronic_sales` sheet contains **20,000 rows** and **19 columns**:

| Column | Description |
|--------|-------------|
| `Customer ID` | Unique customer identifier |
| `Age` | Customer age |
| `Gender` | Male / Female |
| `Loyalty Member` | Yes / No |
| `Product Type` | Laptop / Smartphone / Smartwatch / Tablet / Headphones |
| `SKU` | Product SKU code |
| `Rating` | Customer rating (1–5) |
| `Order Status` | Completed / Cancelled |
| `Payment Method` | Credit Card / Debit Card / PayPal / Bank Transfer / Cash |
| `Total Price` | Total order value (₹) |
| `Unit Price` | Per-unit price (₹) |
| `Quantity` | Number of units purchased |
| `Purchase Date` | Date of transaction |
| `Shipping Type` | Standard / Express / Overnight / Same Day / Expedited |
| `Add-ons Purchased.1` | Primary add-on (Accessory / Extended Warranty / Impulse Item) |
| `Add-ons Purchased.2` | Secondary add-on |
| `Add-ons Purchased.3` | Tertiary add-on |
| `Add-on Total` | Total add-on cost (₹) |
| `Loyalty Score` | Formula-computed score: `IF(Loyalty="Yes", (TotalPrice × Qty) / Age, 0)` |

---

## 📋 Data Highlights

| Attribute | Details |
|-----------|---------|
| Total Records | 20,000 |
| Date Range | 2023 – 2024 |
| Gender Split | Male 50.8%, Female 49.2% |
| Loyalty Members | 4,343 (21.7%) vs 15,657 Non-members |
| Completed Orders | 13,432 (67.2%) |
| Cancelled Orders | 6,568 (32.8%) |
| Top Product by Volume | Smartphone (5,978 orders) |
| Top Product by Revenue | Smartphone (₹2.15 Cr) |
| Most Common Payment | Credit Card (5,868 orders) |
| Most Common Shipping | Standard (6,725 orders) |

---

## 🔑 Key Insights

- **Smartphones** dominate both by order volume and total revenue — contributing nearly **34%** of total sales.
- **32.8% cancellation rate** is notable and may indicate fulfilment or satisfaction issues worth investigating.
- Only **21.7% of customers** are loyalty members, suggesting a large opportunity for loyalty program expansion.
- **Add-ons are evenly distributed** across Accessory, Extended Warranty, and Impulse Items — each ~33%.
- **2024 accounts for 86%** of all transactions (17,302 of 20,000), reflecting a strong sales ramp-up.
- **Average unit price** is ₹578, with Laptops typically commanding the highest individual prices.

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Slicers, Bar Charts, Pie Charts, Line Charts, IF Formulas

---

## 📄 License

This dataset is intended for sales analytics, business intelligence, and educational purposes.
