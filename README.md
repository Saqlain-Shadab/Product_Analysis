# 📊 Product Sales Analysis

**Problem Statement**  
The objective of this project is to analyze sales performance, profitability, and shipment data for **Awesome Chocolates**. The analysis will provide insights into total sales, profit margins, regional sales distribution, and individual sales personnel performance. The findings will help optimize sales strategies and improve business decision-making.

---

**Data Sources**  
The data for this project comes from an Excel file containing:

- **Shipment Data**: Includes details of each shipment, such as sales, boxes, and shipment dates.  
- **Dimension Data**: Includes product details, sales team information, and geographical data.  
- **Calendar Table**: Provides date-based references for time-series analysis.

---

**Data Cleaning**  

- Removed unnecessary rows and columns from all datasets.  
- Standardized column names for consistency.  
- Converted date fields to proper datetime format.  
- Transformed numerical columns (Sales, Cost per Box, etc.) to appropriate data types.  
- Handled missing values and eliminated duplicate records.

---

**Data Modelling**  

The data model follows a **star schema** approach with:

- **Fact Table**:  
  - Shipments (contains transactional sales data)

- **Dimension Tables**:  
  - Sales-Person Table: Contains details of sales representatives.  
  - Product Table: Contains product details, including categories and costs.  
  - Geography Table: Contains geographical regions for sales analysis.  
  - Calendar Table: Helps in time-based analysis.

---

**DAX (Data Analysis Expressions)**  

- Created calculated measures to derive total sales, profit margins, and shipment counts.  
- Implemented running totals, year-over-year comparisons, and month-over-month growth calculations.  
- Defined relationships between fact and dimension tables to enhance analytical capabilities.

---

**Data Visualization**  

Developed an interactive **Power BI dashboard** featuring:

- Total Sales, Total Shipments, and Total Profit metrics  
- Sales and Profit trends over time  
- Salesperson performance rankings  
- Regional sales distribution  
- Product category-wise sales breakdown

---

**Data Analysis**  

- Identified top-performing sales personnel based on revenue and profit contribution.  
- Analyzed profitability by product category to determine the most and least profitable products.  
- Evaluated regional sales trends to understand geographic performance.  
- Detected seasonal trends using time-series analysis.

---

**Expected Outcome**  

- A comprehensive sales performance dashboard for monitoring key business metrics.  
- Insights into high-revenue products and regions to optimize sales strategies.  
- Identification of underperforming areas to improve efficiency.  
- Data-driven decision-making for improving profitability and shipment logistics.
