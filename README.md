# Retail Sales Performance Dashboard

# Project Description

This repository hosts an interactive Retail Sales Performance Dashboard designed to analyze revenue dynamics, track Year-over-Year (YoY) growth, evaluate product categories, and monitor customer purchasing behaviors. By converting raw retail transaction records into high-impact visual intelligence, this dashboard equips business leaders and inventory managers with the insights needed to optimize supply chains, target high-value clients, and maximize overall profitability.

# Strategic Business Goals

The dashboard is engineered to drive data-backed decisions across several key operational areas:

* Evaluating Year-over-Year (YoY) Growth: Identifying trajectories in revenue and sales volume to verify business health.
* Streamlining Inventory Management: Pinpointing top-selling items and categories to align stocking levels with market demand.
* Analyzing Channel Performance: Comparing In-Store versus Online sales channels to optimize distribution resources.
* Cultivating High-Value Accounts: Tracking spending patterns of top-tier customers to support exclusive loyalty initiatives.
* Historical Trend Analysis: Visualizing revenue distribution across fiscal years to understand long-term growth patterns.

# Technologies Utilized

* Data Visualization: Power BI Desktop
* Data Engineering & ETL: Power Query (Data cleaning, normalization, and modeling)
* Analytical Calculations: DAX (Data Analysis Expressions) for custom time-intelligence and KPI formulas

  # Dashboard Preview
  https://github.com/Oreoluwa456/Retail-store-sales/blob/main/image.png

  # dataset Used
  https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning

# Core Business Metrics

The top panel of the dashboard tracks four crucial indicators of retail momentum, highlighting significant gains compared to the previous year (PY):

* Total Revenue: **$1.47M** (**+48.1% vs. PY**)
* Active Customer Base: **25** (**0.0% vs. PY**)
* Average Order Value (AOV): **$129.60**
* Total Volume Sold: **63K units** (**+47.6% vs. PY**)

# Analytic Views and Visual Features

* Top 10 Best-Sellers: A bar chart ranking individual inventory items, highlighting high-performing stock-keeping units (SKUs) such as *Item_25_FUR* and *Item_25_EHE*.
* Omnichannel Comparison: A dual-line chart tracking monthly quantity sold across In-Store and Online channels to spot seasonal shifts and channel preferences.
* VIP Customer Tracking: A donut chart and underlying area trend visual monitoring the top 5 spending customers (led closely by *CUST_24* at 20.35% and *CUST_05* at 20.11%).
* Revenue by Product Line: A horizontal ranking of primary retail categories, highlighting *Butchers*, *Electric essentials*, and *Beverages* as dominant revenue drivers.
* Yearly Contribution: A donut chart showing the breakdown of total sales across fiscal years (2024 leading with 33.9%, closely followed by 2022 and 2023).

# Category Performance Matrix

The dynamic matrix table provides deep visibility into margins, pricing structures, and transaction quantities across categories:

| Category | Quantity Sold | Avg. Price Per Unit | Total Revenue |
| :--- | :---: | :---: | :---: |
| **Butchers** | 7,774 | \$35,824.00 | \$197,426.00 |
| **Electric household essentials** | 7,897 | \$34,957.50 | \$192,441.50 |
| **Beverages** | 7,974 | \$33,290.50 | \$187,978.50 |
| **Furniture** | 8,083 | \$33,973.00 | \$186,527.00 |
| **Food** | 7,925 | \$33,066.50 | \$184,645.00 |
| **Computers & electric accessories** | 7,832 | \$32,333.50 | \$180,902.50 |
| **Patisserie** | 7,515 | \$31,524.50 | \$172,330.50 |
| **Milk Products** | 7,889 | \$30,411.00 | \$170,747.50 |
| **Total** | **62,889** | **\$265,380.50** | **\$1,472,998.50** |

# Data-Driven Discoveries

* The Retention Paradox: While total customer count remained entirely flat (0.0% change), revenue surged by 48.1% and volume increased by 47.6%. This indicates a massive rise in purchase frequency and average order values from existing accounts, rather than new customer acquisition.
* Category Anchors: *Butchers* and *Electric household essentials* generate the highest total revenue despite not having the highest units sold, pointing to strong pricing power and high unit values in these segments.
* Frictionless Channel Parity: Online and In-store sales volumes run remarkably close throughout the year, though online sales show a strong surge in early winter (January), while in-store shopping peaks during mid-summer.

# Strategic Action Plan

* Launch Customer Acquisition Campaigns: Since customer growth is flat (stuck at 25), the business should introduce referral programs or targeted digital marketing to expand the client funnel.
* Capitalize on Winter Online Surges: Allocate more digital advertising spend toward online channels in November and January to capture the proven seasonal online spikes.
* Targeted VIP Loyalty Programs: The top 5 customers generate a significant portion of overall revenue. Creating a tier-one premium rewards program tailored specifically to *CUST_24* and *CUST_05* can protect this vital revenue stream.
* Price Optimization on High-Volume Items: *Furniture* has the highest quantity sold (8,083 units) but ranks 4th in total revenue. A slight upward adjustment in unit pricing for high-demand furniture lines could significantly lift overall margins.

# Closing Summary

The Retail Sales Performance Dashboard highlights a highly resilient business model marked by massive YoY revenue and volume expansion. By shifting focus toward customer acquisition while maintaining current high-value customer satisfaction, the business can build on its solid \$1.47M foundation and unlock new areas of growth.
