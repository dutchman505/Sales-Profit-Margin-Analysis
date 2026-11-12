# Sales & Profit Margin Analytics Dashboard (Power BI)

This project provides a comprehensive data-driven analysis of corporate sales, revenue, and profit margins, while evaluating performance across managers and product categories using Power BI[cite: 5, 6].

## Project Structure
- **Sales & Profit Analytics.pbix**: The core Power BI file containing data models, relationships, custom DAX measures, and interactive dashboards[cite: 7].
- **dashboard/**: Visual exports and screenshots of the project:
  - `sales_overview.png`: Overview of total sales, annual growth, monthly trends, gender breakdown, and customer segment distribution[cite: 6].
  - `profit_margin_analysis.png`: Manager and category breakdowns detailing revenue, margin strength, and profit margin percentages[cite: 5].

---

## Dashboard Overview & Pages

### 1. Sales and Profit Analysis (Page 1)
The primary macro-level overview tracking overall business performance[cite: 6]:
- **Key Performance Indicators (KPIs):** Total Revenue (6.58M ₼), Total Profit (2.51M ₼), Customer Count (500), Order Count (5,200), and YoY Growth Rate (46.77%)[cite: 6].
- **Monthly Performance:** Column chart showing total revenue alongside a line chart tracking year-over-year growth percentages per month[cite: 6].
- **Revenue by Gender:** Donut chart displaying the percentage share of revenue from female and male customers[cite: 6].
- **Customer Share by Segment:** Distribution across Corporate, Retail, VIP, and Online customer groups[cite: 6].
- **Global Filters:** Interactive filtering options for Year, Month, Category, City, and Sales Channel[cite: 6].

### 2. Profit Margin Analysis (Page 2)
An in-depth profitability analysis focusing on individual managers and product categories[cite: 5]:
- **Revenue and Margin by Manager:** Total revenue, margin strength, and profit margin percentages for each sales manager (e.g., Rauf A., Konul A., Orkhan M., etc.)[cite: 5].
- **Profit Margin by Category:** Detailed margin percentages across product categories ranging from Books to Cosmetics[cite: 5].

---

## Tech Stack & Custom DAX Measures
Technologies and custom formulas used within the project[cite: 7]:
- **Power BI Desktop & Power Query**: Data extraction, transformation, cleaning, and modeling (ETL).
- **Core DAX Measures**[cite: 7]:
  - `Total Revenue` = SUM(...)[cite: 7]
  - `Total Profit` = SUM(...)[cite: 7]
  - `Profit Margin %` = [Total Profit] / [Total Revenue][cite: 5, 7]
  - `YoY Growth Rate`[cite: 6, 7]
  - `Order Count` & `Unique Customer Count`[cite: 6, 7]
  - Navigation and page-switching buttons powered by custom DAX logic[cite: 7].

---

## How to Use
1. Download the **`Sales & Profit Analytics.pbix`** file from the repository[cite: 7].
2. Open the file using **Power BI Desktop**[cite: 7].
3. Use the top filter panels to interactively explore data across different years, categories, and regions[cite: 5, 6].
