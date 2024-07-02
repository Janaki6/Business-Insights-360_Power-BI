# Business-Insights-360

Link to Business Insights 360 Presentation document
Link to Live Interactive DashBoard: [Power BI DashBoard](https://app.powerbi.com/groups/5082762d-bb99-48de-9870-8a8aaa8553d7/reports/2f3ee310-07f4-47de-abb6-ea35c345e74d/ReportSection375f6b10035b2ce223b8?experience=power-bi)

**Project Overview**

AtliQ Hardware is rapidly expanding and has decided to use PowerBi for the first time to execute data analytics. The Business Insights 360 dashboard should be built using Microsoft Power BI. 
This multi-functional dashboard should be tailored in such a way that it should provide AtliQ Hardware with vital insights into their many departments such as Finance, Sales, Marketing, and Supply Chain 
on a worldwide scale. Also due to the lack of effective analytics the company faced a major loss in Latin America. Senior executives of this company have decided to invest in a data analytics project 
and have assigned a team for this work.

**About AtliQ Hardware**

AtliQ Hardware is a rapidly growing company that operates globally. They sell computer and computer accessories through three channels:

•	Retailers

•	Direct

•	Distributors


**Importing Data into SQL**

Importing the AtliQ's data into the MySQL Workbench. The data includes both fact and dimension tables.


**Tables:**

**Dimension Tables**

**dim_customer**

o	75 distinct customers throughout the market

o	2 types of platforms: Brick & Mortar (Physical/offline store) and E-commerce (Online Store)

o	Three channels: Retailer, Direct, Distributors

**dim_market**

o	27 distinct markets (e.g., India, USA, Spain)

o	7 sub-zones

o	4 regions: APAC, EU, nan, LATAM

**dim_product**

o	Divisions: P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, Storage

o	14 different categories (e.g., Internal HDD, keyboard)

o	Different variants available for the same product

**Fact Tables**

**fact_forecast_monthly**

o	Used to forecast the customer’s need in advance, leading to higher customer satisfaction and reduced storage costs.

**fact_sales_monthly**

o	Similar to the fact_forecast_monthly table, but with actual sold quantities.

**Miscellaneous Data**

•	**Gross_price**: Base price set for product.

•	**Pre_invoice_deductions**: Discount to customer set at the beginning of financial year.

•	**Net Invoice sale** = Gross price - Pre_invoice_deductions

•	**Post_invoice_deduction**s: Details of post-invoice deductions and other deductions (Promotional offers, Placement fees and Performance Rebate)

•	**Net Sales**: Net Invoice sale - Post_invoice_deductions

•	**COGS (Cost of Goods Sold)**: Manufacturing cost + Freight cost (Transportation) + other cost

•	**Gross Margin** : Nest Sales – COGS cost

**Import data to Power BI**

After exploring the data, we now connect and load the AtliQ's data from MySQL database to the Power BI. The Targets and Market Share data excel file, related information’s are imported to Power BI.

**Data Modelling**

•	Cleaning, formatting and transforming the data using power query

•	Establishing relationships among the tables, employing either Star Schema or the Snow Flake methodology.

•	Subsequently, conducting data validation against the benchmarks set by the stakeholders
   
**Dashboard Designing**

Based on mockups received as requirements, the team will start designing visuals and creating measures as needed.

**Home View**

In the Home view, all the view buttons will be accessible. Users will land on specific view pages by clicking the button and you can navigate to the certain view.


**The different views are:**

**Info**: User manual and get to know the key information of this tool.

**Finance**: It enables users to analyze P&L statements for any customer/product/country, understanding the net sales and exploring other fiscal metrics

**Sales**: Analyzing the performance of customer(s) over key metrics like Net Sales, Gross Margin and view the same in profitability / Growth matrix.

**Marketing**: Analyzing the performance of product(s) over key metrics like Net Sales, Gross Margin and view the same in profitability / Growth matrix.

**Supply Chain**:	Get Forecast Accuracy, Net Error and risk profile for product, segment, category, customer etc.

**Executive**:	A top level dashboard for executives consolidating top insights from all dimensions of business.

**Support**: Issues resolution by connecting to support specialist.

**Project Outcomes**

This dashboard helps with various business questions in different situations. It enables data-driven decisions to make AtliQ more profitable. It uses data to answer many 'why' questions in different scenarios.


