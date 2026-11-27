# 📊 Sales Performance Dashboard (Power BI)

An interactive, multi-page **Power BI** dashboard that analyzes sales, profit, customers and operations for a retail business, with all values in **INR (₹)**. It turns raw order-level data into clear visuals so that management can quickly see what is selling, where, and how profitable it is.

## 🎯 Objectives

- Track overall **Sales, Net Sales, Profit, Discount and Order count**
- Find the best and worst performing **categories, sub-categories and regions**
- Understand **customer segments**, sales channels and payment methods
- Identify **top cities and locations** driving sales and profit
- Provide a detailed drill-down report for business review

## 🗂 Dashboard Pages

| # | Page | What it shows |
|---|------|---------------|
| 1 | **Overall Sales Performance** | KPI cards (Sales, Net Sales, Profit, Discount, Orders), sales by category, customer segment donut, region/segment columns |
| 2 | **Category Sales Performance** | Net sales by region, category sales, sales trend over time by region, sub-category funnel |
| 3 | **Profit & Product Analysis** | Profit by region, profit vs sales by category/sub-category, region-wise net sales and profit |
| 4 | **Customer & Operations Analysis** | Sales by segment, channel, payment method, shipping days and category split |
| 5 | **Geographical Analysis** | City-wise sales map, profit by city, region/category treemap |
| 6 | **Detailed Business Report** | Matrix tables with Sales, Net Sales, Profit and Quantity by category, sub-category and region |

## 🛠 Tools & Skills Used

- **Power BI Desktop** – data modeling, visuals, slicers, drill-down
- **DAX** – measures and calculated fields
- **Power Query** – data cleaning and transformation
- **Excel / CSV** – source data

## 🔑 Key Fields

`Order_ID` · `Order_Date` · `Region` · `City` · `Category` · `Subcategory` · `Segment` · `Channel` · `Payment_Method` · `Shipping_Days` · `Quantity` · `Sales_INR` · `Discount_Amount_INR` · `Net_Sales_INR` · `Profit_INR`

## 📈 Key Insights

> *(Replace with your real findings from the dashboard)*

- [Top category by sales, e.g. Technology] contributes the highest share of sales
- [Region] is the highest-profit region, while [Region] needs improvement
- [Segment] customers generate the largest share of revenue
- Discounts of [x%] affected profit in [category]

## 🖼 Screenshots

![Overall Sales Performance](screenshots/page1.png)
![Profit and Product Analysis](screenshots/page3.png)

## 📁 Repository Structure

```
├── karthickraja_sale_report.pbix   # Power BI report file
├── screenshots/                    # Dashboard page images
└── README.md
```

## ▶️ How to Open

1. Download the `.pbix` file from this repository
2. Open it in **Power BI Desktop** (free)
3. Use the page tabs and slicers to explore the report

## 🙋 Author

**Karthik Raja K** – B.Com (Computer Applications) graduate | Salem, Tamil Nadu
📧 karthickkamaraj3@gmail.com · 🔗 [GitHub](https://github.com/karthickkamaraj3-cpu)
