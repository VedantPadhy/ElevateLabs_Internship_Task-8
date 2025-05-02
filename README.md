# ElevateLabs_Internship_Task-8
Simple Sales Dashboard Design 
Objective: Create a basic interactive dashboard that shows sales performance by product, region, and month
# Superstore Sales Performance Dashboard

## Objective
Create a dynamic and interactive dashboard to visualize sales performance by **Product**, **Region**, and **Month**, using the **Superstore Sales dataset**.

---

## 🛠️ Tools Used
- **Power BI** (for dashboard creation and data modeling)
- *(Optional)* Python (Pandas) for pre-cleaning CSV

---

## Dataset Info
**File**: `Sample-Superstore.csv`  
**Key Columns**:
- Order Date, Region, Category, Sub-Category
- Sales, Profit, Quantity, Discount

---

##  Dashboard Features

### Data Preprocessing
- Converted `Order Date` to `Month-Year` using Power BI DAX:
  ```DAX
  MonthYear = FORMAT('Superstore_Sales'[Order Date], "MMM-YYYY")

Visual Components
Line Chart – Sales trend over each Month-Year


Bar Chart – Sales performance by Region


Donut Chart – Sales distribution by Category


Slicer – Filter by Region to see region-specific insights


KPI Cards – Total Sales, Total Profit, and Total Orders


Profit Margin Bar Chart – Avg. Profit Margin by Category


Top 5 Products Table – Products with highest sales + profit bars



 Insights
West Region recorded the highest total sales across multiple months.


Technology Category outperformed in revenue but had fluctuating margins.


Top 5 products contributed over 20% of total sales—highlighting a winner-take-most trend.
