## Shopify Sales Analysis: Customer Loyalty & Revenue Growth  

## Business Problem / Objective  

Shopify management wants to understand both customer loyalty health and revenue growth drivers from a one-week snapshot of U.S. transactions.  

The business needs clear visibility into:  

- How sales and order volumes trend across days of the week  
- Which products and payment gateways drive revenue  
- Who the top customers are and how loyal they remain  
- Which regions and cities perform best or worst  
- Where opportunities exist to improve retention and maximize revenue  

This project answers the core question:  

How can Shopify optimize sales performance while strengthening customer loyalty to drive sustainable growth?  

## Dataset Overview  

- Data Source: Shopify transactional sales records obtained through web search  

- Time Period Covered: March 18 – March 24, 2025 (1 week)  

- Volume: 7,431 transactions  

- Geography: United States only  

## Key Columns in the Dataset  

- Order Date  
- Product Type (Shoes, Jackets, Accessories, etc.)  
- Quantity Ordered  
- Subtotal, Tax, Total Price (USD)  
- Payment Gateway (Shopify Payments, PayPal, Manual)  
- Customer ID (to track repeat behavior)  
- State (Billing Address Province)  
- City  

## Tools Used  

- Excel / Power Query – Data cleaning and transformation  

- Excel PivotTables & Power Pivot – Data modeling and visualization  

- Excel Slicers – Interactive filtering  

## Data Cleaning & Preparation (Excel / Power Query)  

- Imported Shopify CSV data via Get Data → From Text/CSV  

- Removed duplicate records  

- Standardized date formats for time intelligence  

- Handled missing values in revenue and quantity fields  

- Ensured consistent product and region naming  

- Converted numeric columns to correct data types  

- Built a Calendar Table (Year, Month, Day of Week)  

- Separated Fact Table (Sales Transactions) from Dimension Tables (Customer, Product, Payment Gateway, Date)  

## Data Modeling (Excel)  

- Established relationships between Fact and Dimension tables  

- Created calculated measures in Excel using DAX-like formulas:  

- Net Sales = SUM(Total Price USD)  

- Total Orders = DISTINCTCOUNT(Order Number)  

- Total Customers = DISTINCTCOUNT(Customer ID)  

- Average Order Value (AOV) = Net Sales ÷ Total Orders  

- Lifetime Value (LTV) = Net Sales ÷ Total Customers  

- Purchase Frequency = Total Orders ÷ Total Customers  

- Repeat Customers = Total Customers – Single Order Customers  

- epeat Rate = Repeat Customers ÷ Total Customers  

## Key Questions & Analysis  

- What is the repeat vs single-order customer split?  

= How are total sales and order volumes trending across the week?  

- Which products generate the highest and lowest revenue?  

- What is the average order value (AOV), and how does it vary across customers?  

- Which payment gateways contribute most to revenue?  

- Which regions and cities are top performers?  

- Who are the top-performing customers?  

## Key Insights  

- Net Sales totaled $4.59M across 7,431 transactions in one week  

- Monday was the strongest day ($750K), while Tuesday was the lowest ($576K)  

- Walking Shoes and Climbing Shoes were top revenue drivers ($3.6M combined)  

- Shopify Payments contributed the largest share ($2.68M), followed by PayPal and Gift Cards  

- Washington, Houston, and NYC were the top-performing cities by sales  

- Repeat rate stood at 46%, showing moderate loyalty but room for improvement  

- Top 5 customers contributed over $20K, highlighting customer concentration risk  

## Recommendations  

Focus marketing and promotions on high-performing products such as Walking Shoes and Climbing Shoes  

- Investigate underperforming products such as Water Shoes and Flip-Flops for repositioning or discontinuation  

- Optimize inventory planning for top-performing cities, including Washington, Houston, and NYC  

- Develop loyalty programs to increase repeat rate beyond 50%  

- Expand distribution strategies in high-growth regions  

- Monitor payment gateway performance and encourage use of high-margin channels  

## Dashboard / Visualization (Excel)  

The Excel project contains two main dashboards  

## Are Customers Truly Loyal?  

- Repeat vs single-order customers  

- Lifetime value and repeat rate  

- Top customers by revenue  

- Regional AOV and quantity insights  

- Map visualization of sales by city/province  

## What Drives Revenue Growth?  

- Net sales, orders, AOV, and quantity trends  

- Top and bottom products  

- Payment gateway breakdown  

- Daily revenue trend analysis  

- Quantity vs ASP scatter analysis  

## Conclusion  

This Shopify analysis transformed a one-week transactional dataset into meaningful business insights. It helped  

- Identify key revenue drivers and underperforming products  

- Highlight regional performance gaps  

- Understand customer loyalty and concentration  

- Support data-driven decision-making for growth strategies  

The dashboards provide Shopify stakeholders with a powerful tool to monitor performance and plan strategic improvements.  

## Limitations  

- Dataset covers only one week (March 18–24, 2025), so insights represent a snapshot rather than long-term trends  

- No marketing spend, customer demographics, or competitor data included  

- External factors such as seasonality, economic conditions, and supply chain disruptions were not captured  
I am Abdul‑Azeez Rofiah Kehinde, an E‑commerce Data Analyst specializing in sales, customer behavior, and marketing analytics. I help businesses transform raw transactional data into actionable insights that drive revenue growth, customer retention, and strategic decision‑making. My expertise lies in using tools like Excel, Power Query, SQL, Powe BI to clean, model, and visualize data, delivering dashboards that tell a clear business story and empower stakeholders to act with confidence. Let's connect
