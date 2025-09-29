# AtliQ-Hardware-Business-Insights-360

Video Presentation Link: [Link]()

## Table of Contents

1. [Project Overview](#project-overview)
2. [Datasets](#datasets)
3. [Power BI Dashboard Overview](#power-bi-dashboard-overview)
4. [Power BI Techniques Learned](#power-bi-techniques-learned)
5. [Tools Used](#tools-used)
6. [Business Terms Learned](#business-terms-learned)

## Project Overview

AltiQ Hardware, a fast-growing global company, specializes in selling computers and accessories through three primary channels: retailers, direct sales, and distributors. Despite its rapid growth, the company encountered unexpected losses after opening a new store in America. These challenges were initially identified through surveys, intuition, and basic Excel analysis.

With competitors leveraging advanced analytics teams, AltiQ Hardware recognized the pressing need to build robust analytics capabilities to remain competitive in the industry.

To gain an edge and embrace data-driven decision-making, AltiQ Hardware initiated the implementation of Power BI for analytics. The goal of this project was to equip stakeholders with actionable insights across finance, sales, marketing, and supply chain functions, enabling informed decision-making at every level.

I contributed to this transformative project by applying skills gained from the Codebasics Power BI Course, ensuring a structured approach to developing impactful dashboards and reports.

Link for the Business Insights 360 Dashboard - [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzA2ZTVkZGUtYzEyYy00ZTBlLWEzZjMtMDE1ODE2NDVmNWNiIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


## Datasets

Before diving into analysis, it is crucial to understand the datasets. The datasets consist of two tables:

Dimension table: Static data like customer and product details.

Fact table: Transaction data.

gdb041:

- dim_customer
- dim_market
- dim_product
- fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
- fact_sales_monthly - This table is more or less is similar as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:

- freight_cost
- gross_price
- manufacturing_cost
- Pre_invoice_dedutions
- Post_invoice_deductions

### The Importance of Data Modeling in Analytics

For this project, data was imported from MySQL into Power BI, where it was cleaned, transformed, and structured into a robust data model. But why is data modeling so critical for analysis?

If we break down the work of a data analyst, it typically involves four key steps:

✅ Data Extraction → ✅ Data Cleaning → ✅ Data Modeling → ✅ Data Analysis

The third step—Data Modeling—is indispensable if you want to reach the final step, Data Analysis. It serves as the backbone of any analytical report. A well-designed data model not only ensures accurate and efficient analysis but also enhances report performance and interactivity. Poor modeling, on the other hand, can lead to sluggish reports and unreliable insights.

In this project, we adopted the Snowflake schema for data modeling, ensuring a scalable and optimized foundation for building meaningful visualizations and reports.

![Data Modelling image](![DM1](https://github.com/user-attachments/assets/f1c27267-a50a-4380-b361-afd35e16d045)

## Power BI Dashboard Overview

The dashboard comprises six pages

#### Home Page: A landing page with buttons to navigate to different pages.

![image]()

#### Finance Page Overview: This page is designed to enhance financial planning, optimize budgeting processes, and implement effective cost control measures. Key insights provided include:

- Profit and Loss Statements: A comprehensive view of financial performance.
- Top and Bottom Products by Net Sales: Identify the most and least profitable products.
- Top and Bottom Customers by Net Sales: Highlight key customer segments driving revenue and those requiring strategic attention.

By focusing on these metrics, the Finance Page ensures stakeholders can make informed financial decisions to drive business growth.

![image]()

#### Sales Page Overview: The Sales Page is designed to drive revenue growth and expand market share by providing actionable insights. Key features include:

- Customer Performance by Net Sales: Analyze customer contributions to overall sales.
- Gross Margin and Gross Margin %: Evaluate profitability and efficiency across products or services.
- Additional Sales Metrics: Dive deeper into trends and patterns to uncover growth opportunities.

This page empowers decision-makers with the insights needed to refine strategies, enhance customer engagement, and maximize profitability.

![image]()

#### Marketing Page Overview: The Marketing Page focuses on enhancing brand visibility and fostering customer engagement through data-driven insights. Key features include:

- Segment Performance by Gross Margin %: Assess the profitability of different market segments.
- Segment Performance by Net Profit %: Evaluate the net profitability across customer or product categories.
- Additional Marketing Metrics: Uncover trends and opportunities to refine marketing strategies.

This page equips stakeholders with the tools to identify high-performing segments, optimize campaigns, and boost overall marketing effectiveness.

![image]()

#### Supply Chain Page Overview: The Supply Chain Page is designed to optimize inventory management and strengthen supplier relationships to achieve significant cost savings. Key insights include:

- Forecast Accuracy: Measure the precision of demand forecasting to reduce overstock and stockouts.
- Net Error: Analyze discrepancies between forecasted and actual demand.
- Additional Supply Chain Metrics: Identify opportunities to streamline operations and improve efficiency.

This page empowers decision-makers with the data needed to enhance supply chain performance, minimize waste, and maximize cost-effectiveness.

![image]()

#### Executive Page Overview: The Executive Page offers a comprehensive performance overview tailored for top management, enabling quick and informed decision-making. Key highlights include:

- Net Sales: A snapshot of overall revenue performance.
- Gross Margin % and Net Profit %: Key profitability metrics to assess financial health.
- Revenue Contribution by Channel: Analyze performance across Retail, Direct Sales, and Distributors.
- Top 5 Customers and Products: Identify key revenue drivers.
- Sub-Region Performance: Evaluate geographical performance for targeted strategies.
- Additional Metrics: Provide a holistic view of the organization's operations and outcomes.

This page consolidates critical metrics into a high-level dashboard, ensuring executives stay informed and aligned with organizational goals.

![image]()


## Power BI Techniques Learned

1. Asking the right questions before starting a project
2. Creating calculated columns
3. Creating measures using the DAX language
4. Data modeling
5. Using Bookmarks to switch between visuals
6. Page navigation with buttons
7. Preventing zero division errors using the divide function
8. Dynamic titles based on applied filters
9. Using KPI indicators
10. Conditional formatting of visual values with icons or background colour
11. Data validation techniques
12. Publishing reports to Power BI services
13. Setting up a personal gateway for data auto-refresh
14. Creating Power BI Apps
15. Collaborating, managing workspaces, and setting access permissions in Power BI services

## Tools Used

SQL, Power BI Desktop, DAX language, DAX studio (to reduce file size), Project Charter file.

## Business Terms Learned

Gross Margin, Gross Margin %, Gross Sales, Gross Sales %, Pre-invoice deductions, Post-invoice deductions, Net sales, Net Invoice Sales, Net Profit, Net Profit %, COGS (cost of goods sold), YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.
