#  Sales Insights Dashboard using Power BI

The Sales Insights Dashboard is a business intelligence solution built for a computer hardware company in India. It converts raw Excel-based sales data into actionable insights, helping the Sales team monitor and optimize performance across regions, products, and time using Power BI.


##  Dashboard Preview



[Dashboard Screenshot](https://drive.google.com/file/d/1i1FbuRqosOMYwQULeJJmzZ4sbQP2IGtH/view?usp=sharing)

[Download Power BI File](https://drive.google.com/file/d/1JK63lxKUdyoLoEaQ_PQZNwYkgoBYHzBR/view?usp=sharing)





##  Project Overview

The company faced challenges with fragmented Excel reporting and lacked centralized visibility into sales performance. This project solves those issues by building an interactive Power BI dashboard using the provided Excel dataset as the data source.



##  Objectives

- Visualize sales and revenue trends from 2017 to 2020.
- Monitor performance by region and customer.
- Identify top-selling products and highest-grossing customers.
- Replace static Excel reports with a dynamic Power BI dashboard.
- Leverage Power BI not just for visualization but also for data transformation (ETL).



##  Tools & Technologies

- Power BI Desktop.
- Power Query (M Language).
- Microsoft Excel.
- Star Schema Data Modeling.



##  Installation & Setup

1. Install [Power BI Desktop](https://powerbi.microsoft.com/).
2. Open the project file:
   - Load `Sales_Insights_Dashboard.pbix`.
   - Ensure `sales.xlsx` is in the same directory (or update the data source path).



##  Data Cleaning & Transformation (ETL in Power BI)

Performed via Power Query. Key transformation steps:

- **Currency Conversion**: Converted all values from USD to INR for consistency.
- **Invalid Entries Removed**: Removed records with incomplete city data (e.g., "New York", "Paris").
- **Negative Sales Removal**: Filtered out rows with negative or zero sales amounts.
- **Data Normalization**: Created a clean column for uniform currency comparison.



##  Dashboard Features

- **Total Revenue Analyzed**: ₹13 Million.
- **Total Sales Quantity**: 10,000+ Units.
- **Year-over-Year and Monthly Trends.**
- **Region-wise Sales**: Highest revenue from Mumbai and Delhi.
- **Top Products**: Prod018, Prod016, Prod005.
- **Top Customers**: 5 customers generated over ₹8 Million.
- **Revenue Drop**: Detected post-July 2019.
- **Dynamic Filters**: Slicers for year, month, region, product, and customer.
- **Data Quality Boost**: Improved by 6% after cleaning.
- **85% Time Reduction**: Compared to manual Excel reporting.



##  Key Insights

- Mumbai generated the highest revenue (₹2M+), followed by Delhi.
- Delhi recorded the highest sales volume (5K+ units).
- Top 5 customers contributed 60%+ of total revenue.
- A sharp decline in revenue is observed post-July 2019.
- Seasonal purchase trends are evident.



##  Future Improvements

- Add cost/profit analysis for financial KPIs.
- Introduce real-time data updates via Excel/CSV connectors.
- Expand scope to inventory and logistics dashboards.
- Implement user-level access and responsive/mobile views.



##  Contributing

Feel free to fork, clone, and submit pull requests. Suggestions and improvements are always welcome.



##  Contact

**Developed by**: Satyam Sule  

**Email**: sulesatyam68@gmail.com  

**LinkedIn**: [Satyam Sule](https://www.linkedin.com/in/satyamsule)


