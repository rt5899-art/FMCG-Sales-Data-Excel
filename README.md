# FMCG Sales Dashboard Project

## Project Overview
This project involves the development of a comprehensive business intelligence and analytics solution designed for a Fast-Moving Consumer Goods (FMCG) company. Centered around the core data repository file FMCG Sales Dashboard.xlsx, the dashboard translates large volumes of daily sales logs, distributor transactions, and product metrics into an interactive executive tool. By analyzing performance across various brand portfolios, distribution networks, and regional markets, the project enables sales managers and supply chain leaders to evaluate distribution efficiency, track brand health, and optimize high-velocity product configurations.

## Requirements
To meet the high-volume operational standards typical of the FMCG sector, the project fulfills the following core requirements:

Multi-Tiered Data Aggregation: Consolidation of raw tables spanning customer accounts, geography, daily product dispatches, and sales targets into a highly optimized data model within FMCG Sales Dashboard.xlsx.

Volume and Value Metric Tracking: Synchronized calculation of both value-based metrics (Gross Revenue, Net Sales, Trade Discounts) and volume-based metrics (Units Shipped, Case Volume, Out-of-Stock incidence rates).

Channel Distribution Analytics: Implementation of granular filtration logic to evaluate performance differences across modern trade, traditional retail markets, e-commerce channels, and direct wholesale.

Scalable Data Loading Framework: A localized layout built to smoothly absorb frequent, high-volume transactional updates without slowing down execution or breaking data hierarchies.

## Tools and Technologies
Microsoft Excel (Advanced Data Modeling Engine): The primary platform used to structure data, map relational tables, and create user-facing visual layouts inside FMCG Sales Dashboard.xlsx.

Power Query Engine: Used for the Extract, Transform, Load (ETL) phase to standardize product descriptions, clean missing distributor data, format timestamps, and build calculated key metrics.

Advanced Cross-Filtering Formulas: Implementation of specialized logical lookup and aggregation math—such as SUMIFS, COUNTIFS, INDEX/MATCH, and dynamic arrays—to build flexible data summaries.

Pivot Tables and Pivot Charts: Utilized to break down large data rows by brand, territory, and channel, instantly changing the visual reporting state based on user inputs.

Interconnected Slicers and Timelines: Built into the main presentation sheet to serve as a clean navigation menu, allowing users to alter the entire report scope with a single click.

## Challenges Faced
Massive Transactional Volumetrics: FMCG data scales quickly, and processing thousands of rows across dozens of product variations often created performance lag. Overcoming this required removing redundant formulas and leaning heavily on Excel's optimized internal cache systems.

Channel and Margin Complications: Properly modeling revenue alongside variable distributor discounts, promotional rebates, and returns created initial reporting discrepancies. This required establishing strict data-clearing rules to ensure gross-to-net financial clarity.

Information Density Control: Presenting volume metrics, value metrics, brand categories, and channel parameters simultaneously risked overwhelming the end-user. The solution required an iterative UI design focused on layout hierarchy and consistent color maps.

## Key Insights
The Pareto Principle in Product Portfolios: A small, specific set of core SKUs (Stock Keeping Units) drives the vast majority of volume and revenue, indicating that protecting the supply chain for these top items is critical to business health.

Inefficiencies in Promotional Spending: Cross-referencing promotional calendars with volume spikes revealed that certain steep trade discounts failed to generate profitable repeat orders, highlighting a need to re-evaluate trade marketing strategies.

Regional Distribution Disconnects: Combining geography and channel analytics showed that high-demand urban sectors frequently faced stock stress, while secondary traditional trade routes held excess safety stock.

## Recommendations for Future Improvements
Migrate to a Cloud BI Ecosystem: To support true multi-user access and eliminate local file size constraints, the underlying structures of FMCG Sales Dashboard.xlsx should be migrated to a dedicated tool like Power BI or Tableau linked directly to a cloud data warehouse (such as Snowflake or BigQuery).

Automate ERP Data Pipelines: Replace manual spreadsheet data entry with live automated data connections (such as SAP, Oracle, or Microsoft Dynamics connectors) to eliminate manual errors and move from weekly updates to a real-time data flow.

Incorporate Predictive Demand Forecasting: Integrate basic predictive algorithms—such as Python-based ARIMA or Holt-Winters exponential smoothing—to generate seasonal demand projections, helping production plants align directly with market movement.
