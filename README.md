# FMCG Sales Dashboard Project

## Project Overview

This repository contains a Fast-Moving Consumer Goods (FMCG) sales analysis project engineered within a spreadsheet data model. The main purpose of this project is to centralize transactional sales data, distribution channel outputs, and regional logistics metrics into an interactive analytical cockpit. By providing real-time visibility into brand performance, purchase orders, and regional revenue pacing, the dashboard addresses the problem of delayed operational reporting, allowing FMCG stakeholders to quickly isolate low-margin segments and optimize supply chain fulfillment timelines.

## Requirements

Microsoft Excel (2019, 2021, or Microsoft 365 recommended)

System Memory: Minimum 4 GB RAM (8 GB recommended for multi-year transactional datasets)

Operating System: Microsoft Windows or macOS

Prerequisites: Advanced Excel features enabled (Pivot Tables, Slicers, and Advanced Data Formatting)

## Tools and Technologies

Core Spreadsheet Platform: Microsoft Excel

Data Aggregation & Structuring: Excel Pivot Tables

Interactivity Control: Multi-Field Slicers (Timeline, SKU, Segment)

Visualization Layer: Excel Pivot Charts (Line, Clustered Column, and Donut charts)

## Challenges Faced

Overcrowded Brand Axis Labels: Attempting to plot revenue for a dense catalog of internal product brands (such as JuBrand, MiBrand, ReBrand, SnBrand, YoBrand sub-variants) led to overlapping text and unreadable category groupings. This layout limitation was overcome by implementing customized label orientations and adjusting chart canvas margins.

Complex Multi-Attribute Slicer Connections: Ensuring that simultaneous filters on chronological timelines, explicit SKU identifiers, and product segments seamlessly updated all charts without causing structural breakage required building unified data mapping tables across separate sheets.

Currency Formatting Overheads: Standardizing high-volume Indian Rupee (₹) pricing strings alongside raw quantity integers caused calculation inconsistencies within early test blocks. This was resolved by implementing strict custom cell-formatting attributes across the transactional table layer.

## Key Insights

Dashboard Inference:

![image alt](https://github.com/rt5899-art/FMCG-Sales-Data-Excel/blob/main/ss-%20FMCG%20sales%20dshboard%20excel.png?raw=true)

Based on the aggregated data compiled in the spreadsheet dashboard interface, the following performance trends were identified:

High-Level Operational Key Performance Indicators: The business generated a Total Revenue of ₹1,99,51,301 across the monitored periods. Total Quantity Sold reached 37,99,824 units, operating under an Average Order Value of ₹104.59, an Average Unit Price of ₹5.25, and maintaining an Avg Delivery Time of 3 days.

Temporal Revenue Velocity: Monthly sales trends show sustained growth throughout the first half of the calendar year. Revenue climbs from a low baseline in January (₹11,63,774.83) and February (₹12,40,812.47), building up momentum through the spring before hitting its absolute operational peak in July at ₹20,72,317.43. Following this peak, sales contract through the fall, ending the year with a slight recovery in December at ₹16,55,964.83.

Brand Contribution Matrix: Individual product portfolios exhibit highly varied revenue results. SnBrand2 emerges as the dominant brand leader, generating a massive peak revenue of ₹28,60,430.84. YoBrand4 represents the second most profitable asset at ₹24,73,953.74, while portfolio lines like JuBrand3 and MiBrand2 reflect much smaller revenue contributions.

Regional Fulfillment Discrepancies: Analyzing the sum of delivered quantities across regional boundaries shows that the PL-North sector acts as the primary volume hub, driving 1,14,24,555 units. The PL-South sector matches this pace closely at 1,14,08,432 units, whereas the PL-Central region logs the lowest logistical footprint at 1,13,76,163 units.

Distribution Channel Breakdown: Sales generation is distributed across three main channels. The Discount channel captures the largest overall share of transactions at ₹66,55,587.49, followed closely by traditional Retail channels at ₹66,43,440.51, while E-commerce platforms bring in the remaining revenue share at ₹66,52,273.11.

## Recommendations for Improvements

Maximize Inventory Ahead of the Q3 Seasonal Peak: Since the sales velocity data highlights a clear revenue climb that peaks in July at ₹20,72,317.43, production schedules and warehouse stock levels should be scaled up by 15-20% in late Q2 to capitalize on this high-volume period and prevent regional stockouts.

Replicate SnBrand2 Marketing Strategies: SnBrand2 is the top performer in the portfolio, generating ₹28,60,430.84 in revenue. A detailed product audit should be conducted to isolate why it outperforms the rest of the catalog, allowing the team to apply its pricing models, flavor profiles, or packaging choices to struggling lines like JuBrand3.

Address Logistics Gaps in the Central Region: The PL-Central region represents the lowest distribution tier at 1,13,76,163 units. Supply chain networks should be audited in this territory to determine if the lower volume is caused by infrastructure issues or a lack of local retail partnerships.

Implement Target Promotions on E-commerce Channels: Because revenue is split almost evenly between Discount (₹66,55,587.49), Retail (₹66,43,440.51), and E-commerce (₹66,52,273.11), the digital channel should be prioritized for higher-margin premium SKUs. This will help raise the Average Order Value above the current ₹104.59 benchmark.
