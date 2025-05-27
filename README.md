# Tableau Sales & Customer Dashboards

## 📈 Project Overview  
This project delivers two interactive Tableau dashboards—**Sales Dashboard** and **Customer Dashboard**—to empower stakeholders (sales managers, marketing teams, executives) to explore year-over-year performance, identify trends, and drill into detailed customer and product insights.

---

## 🔎 Dashboards  

**Live Dashboard Links:**
- [Sales Dashboard](https://public.tableau.com/app/profile/ziheng.pan8201/viz/Book1_17482485600180/SalesDashboard)
- [Customer Dashboard](https://public.tableau.com/app/profile/ziheng.pan8201/viz/Book1_17482485600180/CustomerDashboard)

---

### 1. Sales Dashboard  
**Purpose:**  
- Provide a high-level view of total sales, profits, and quantities.  
- Track monthly and weekly performance, compare current vs. prior year.  
- Surface top- and bottom-performing months, subcategories, and weeks.

**Key Features:**  
1. **KPI Overview**  
   - Total Sales, Total Profit, Total Quantity for Current Year vs. Previous Year.  

2. **Monthly Sales Trends**  
   - Line charts showing each KPI by month (current & previous year).  
   - Callouts/annotations on highest- and lowest-performing months.  

3. **Product Subcategory Comparison**  
   - Side-by-side bar charts of sales and profit by subcategory (current vs. prior year).  

4. **Weekly Sales & Profit Trends**  
   - Weekly totals for sales and profit (current year).  
   - Display of average weekly values.  

---

### 2. Customer Dashboard  
**Purpose:**  
- Offer a comprehensive view of customer activity, segments, and loyalty.  
- Help marketing and management teams tailor strategies to drive retention and growth.

**Key Features:**  
1. **KPI Overview**  
   - Total Customers, Sales per Customer, Total Orders (current vs. previous year).  

2. **Monthly Customer Trends**  
   - Line charts for each KPI by month (current & prior year).  
   - Highlight months with highest/lowest values.  

3. **Customer Distribution by Order Count**  
   - Histogram or bar chart showing number of customers by orders placed.  

4. **Top 10 Customers by Profit**  
   - Table ranking the top 10 most profitable customers.  
   - Columns: Rank, Customer Name, # Orders, Current Sales, Current Profit, Last Order Date.  

---

## 🎨 Design & Interactivity  

- **Dynamic Year Selector**  
  - A single filter allowing users to choose any year for both dashboards.  

- **Global Filters**  
  - Product Category & Subcategory  
  - Region, State, City  

- **Interactive Charts**  
  - Clickable bars/points to filter across all views.  
  - Hover tooltips with detailed metrics.  

- **Dashboard Navigation**  
  - Buttons or tabs to switch seamlessly between Sales and Customer dashboards.  

---

## 🛠️ Data & Implementation  

- **Data Sources:**  
  - Sales transactions (date, product, quantity, sales amount, profit)  
  - Customer records (customer ID, name, orders, order dates)  
  - Geography lookup (region, state, city)  

- **Data Prep:**  
  - Clean and blend in Tableau Prep or SQL:  
    - Date hierarchy (year/month/week)  
    - Category/subcategory mapping  
    - Customer order counts and LOD expressions  

- **Calculated Fields & Parameters:**  
  - YoY growth %
  - Weekly average line  
  - Above/Below flags
  
---

## 🚀 How to Use  

1. Download the workbook in the repository or visit the live dashboards at [Sales Dashboard](https://public.tableau.com/app/profile/ziheng.pan8201/viz/Book1_17482485600180/SalesDashboard).
2. Ensure all data extracts are refreshed daily/weekly as needed.  
3. In the published view:  
   - Use the **Year** parameter at the top to switch analysis periods.  
   - Click on any bar, point, or map region to filter all related charts.  
   - Leverage drop-down filters on the left for product and location slicing.  

---

*This README guides you through the structure, features, and usage of the Sales & Customer Dashboards. Adapt and extend it as your data and analysis needs evolve.*  
