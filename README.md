# E-Commerce Sales Analysis Dashboard

A complete end-to-end data analytics project built using **Microsoft Power BI Desktop**, covering data cleaning, data analysis, business insights generation, and interactive dashboard development.

---

## Project Overview

This project involves analyzing e-commerce sales data across multiple Indian states, product categories, and payment modes. The final output is an interactive Power BI dashboard that enables stakeholders to monitor key business metrics and derive actionable insights through dynamic filtering and visual exploration.

---

## Dashboard Preview    <img width="1165" height="657" alt="Screenshot 2026-06-16 215344" src="https://github.com/user-attachments/assets/9d7d90e6-8eb0-4884-8d87-45a0b55111bf" />




## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data storage and initial cleaning |
| Power BI Desktop | Data modeling, DAX measures, and dashboard creation |
| DAX (Data Analysis Expressions) | Custom KPI measure calculations |
| Power Query | Data transformation and type formatting |

---

## Project Workflow

### Step 1: Data Cleaning
- Imported raw dataset into Microsoft Excel
- Identified and removed duplicate records
- Handled missing/null values appropriately
- Ensured date columns (Order_Date) were in correct Date format
- Validated numeric columns: Sales_Amount, Profit, Quantity, Discount

### Step 2: Data Analysis (DAX Measures in Power BI)
Custom measures were created using DAX to calculate core KPIs:

```
Total Sales = SUM(Cleaned_Data[Sales_Amount])
Total Profit = SUM(Cleaned_Data[Profit])
Total Orders = DISTINCTCOUNT(Cleaned_Data[Order_ID])
Average Discount = AVERAGE(Cleaned_Data[Discount])
Total Quantity Sold = SUM(Cleaned_Data[Quantity])
```

### Step 3: Business Insights
The following analytical dimensions were explored:
- Sales performance by State
- Revenue breakdown by Product Category
- Top 5 Products by Total Sales
- Payment Mode distribution across orders
- Monthly Sales Trend over 2023–2024

### Step 4: Dashboard Development
An interactive Power BI report was built with the following visuals:

| Visual | Type |
|---|---|
| Total Sales, Total Profit, Total Orders, Avg Discount, Total Qty Sold | KPI Cards |
| Monthly Sales Trend | Line Chart |
| Payment Mode Distribution | Donut Chart |
| Sales by Product Category | Stacked Bar Chart |
| Top 5 Products by Sales | Stacked Bar Chart (Top N Filter) |
| Sales by State | Table Visual |
| Year, Category, State Filters | Slicers |

---

## Key Metrics (2023–2024)

| KPI | Value |
|---|---|
| Total Sales | ₹5M |
| Total Profit | ₹735.20K |
| Total Orders | 1,475 |
| Average Discount | 15% |
| Total Quantity Sold | 4K |

---

## Business Insights

- **Beauty** emerged as the highest-selling product category
- **Karnataka, Delhi, and Maharashtra** are the top-performing states by revenue
- **Cash on Delivery and Net Banking** are the most frequently used payment modes
- Sales showed a consistent upward trend from January 2023 to mid-2023, followed by seasonal fluctuations

---

## Dataset Columns

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date of purchase |
| Customer_ID | Unique customer identifier |
| City | Customer city |
| State | Customer state |
| Product_Name | Name of product purchased |
| Product_Category | Category of product |
| Payment_Mode | Payment method used |
| Quantity | Number of units sold |
| Sales_Amount | Revenue generated |
| Discount | Discount percentage applied |
| Profit | Net profit from the order |
| Year | Order year |
| Quarter | Order quarter |
| Month_Name | Month name |
| Month_Num | Month number (for correct sorting) |
| Month_Year | Combined month-year label |

---

## Skills Demonstrated

- Data cleaning and preprocessing in Excel
- DAX measure development in Power BI
- Data modeling and relationship management
- KPI design and business metric tracking
- Interactive report development with slicers and cross-filtering
- Visual storytelling through charts and dashboards

---

## How to Use

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. If prompted, update the data source path to point to your local Excel file
4. Interact with slicers (Year, Category, State) to filter the dashboard dynamically

---

## Author

Sammeta Saicharan
Aspiring Data Analyst | Power BI | SQL | Excel  

