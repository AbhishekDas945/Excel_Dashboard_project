__<h1> Indian E-Commerce Sales Analysis Dashboard (Excel | Power Query | Power Pivot | DAX) </h1>__

## __Project Overview__

This project features an end-to-end interactive Indian E-Commerce Sales Analysis Dashboard built in Microsoft Excel. Leveraging Excel's business intelligence stack—Power Query for data transformation, Power Pivot for data modeling, and DAX for custom calculated measures—this dashboard transforms raw transactional data from 2023 to 2025 into actionable insights across 15 Indian states.

## __Key Performance Indicators (KPIs)__

The dashboard tracks six core business metrics at a glance:

<img src= "https://github.com/AbhishekDas945/Excel_Dashboard_project/blob/cd878fac570a95013bac775e0b73837f5e7cb72f/Screenshot%202026-09-25%20202017.png" alt= "Excel Dashboard" width = "600">

## **Tools & Technical Workflow (Excel BI Stack)**

- **Power Query (ETL & Data Cleaning)**: Extracted raw e-commerce dataset, cleaned null/duplicate records, standardized date and currency formats, and performed column transformations before loading clean tables into the Data Model.

- **Power Pivot (Data Modeling)**: Designed an optimized relational Data Model in Power Pivot to seamlessly handle 1,00,000 order records, linking transactional data with lookup dimensions for faster query performance.  

- **DAX (Data Analysis Expressions)**: Created explicit DAX formulas and calculated measures to dynamically compute key metrics, including:

  - **Total Sales & Units Sold**: Aggregated revenue (₹ 2.45B) and volume (5,85,640 units) across filter contexts.   

  - **Average Order Value (AOV)**: Calculated using DIVIDE([Total Sales], [Total Orders]) to accurately return ₹ 24,499 across any selected state or year.   

  - **Customer & Order Aggregations**: Used DISTINCTCOUNT and COUNTROWS functions to track 22,820 unique customers and 1,00,000 total orders, alongside percentage splits for New (17%) vs. Repeat (83%) buyers.  

- **Pivot Charts & Interactive Slicers**: Built dynamic visualizations linked to the Power Pivot Data Model and connected multi-table Year and State slicers for real-time filtering.   

- **Custom UI & Dashboard Design**: Applied modern card layouts, custom icons, and cohesive color formatting for an executive-ready presentation. 

## **Dashboard Features & Visualizations**

- **Dynamic Slicers & Filtering**: Filter the entire dashboard by Year (2023, 2024, 2025) and State (Andhra Pradesh, Bihar, Delhi, Gujarat, Haryana, Karnataka, Kerala, Madhya Pradesh, Maharashtra, Punjab, Rajasthan, Tamil Nadu, Telangana, Uttar Pradesh, and West Bengal).   

- **Distribution Status (Pie Chart)**: Visualizes order fulfillment efficiency across five stages: Delivered (80%), Cancelled (8%), Returned (7%), Failed (3%), and Processing (2%).   

- **New vs. Repeat Customer (Donut Chart)**: Tracks customer loyalty by comparing Repeat Customers (83%) against New Customers (17%).   

- **Monthly Sales Trend (Line Chart)**: Maps month-over-month revenue fluctuations from January to December to highlight seasonal demand peaks.   

- **Top 10 Categories by Sales (Horizontal Bar Chart)**: Ranks product categories by revenue generation across Electronics, Appliances, Home & Kitchen, Furniture, Fashion, Footwear, Bags, Health & Wellness, Sports, and Toys.  

- **Payment Method Breakdown (Column Chart)**: Analyzes customer payment preferences across UPI, Cash on Delivery, Credit Card, Debit Card, Net Banking, Wallet, EMI, Pay Later, Gift Card, and Cardless EMI.   

## 💡 **Key Business Insights**

- **Q4 Festive Season Surge**: Monthly sales grow steadily from January to September (~₹130M–₹195M) before experiencing a sharp upward spike between October and December, peaking at over ₹350M in December.  

- **Category Dominance**: Electronics is the primary revenue driver (generating over ₹1,200M in sales), followed by Appliances as the second-largest category (~₹400M).
 
- **Strong Customer Retention**: Repeat buyers account for 83% of the customer base, demonstrating high platform stickiness and repeat purchasing behavior.   

- **Order Fulfillment & Return Rate**: While 80% of orders are successfully delivered, 15% of total orders are lost to cancellations (8%) and returns (7%), highlighting an opportunity to optimize delivery and quality assurance.   

- **Digital Payment Adoption**: Digital transaction modes lead order volume, followed closely by Cash on Delivery, Credit Card, and Debit Card transactions. 

## **Acknowledgments**

Special thanks to @SatishDhawale sir and Skill Course for the practical training in Power Query, Power Pivot, DAX, and interactive dashboard design in Excel. 
