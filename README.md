# Superstore Sales Analytics — Power BI + Microsoft Fabric + AI Insights

## Overview
An advanced end-to-end analytics project built on the Kaggle Superstore dataset, progressing from Power BI Desktop dashboards to enterprise-grade Microsoft Fabric analytics and AI-powered business insights.

## Tools Used
- Power BI Desktop — data modeling, DAX measures, interactive dashboard
- Microsoft Fabric — Lakehouse, Dataflow Gen2, Semantic Model
- Power BI AI Visuals — Q&A, Key Influencers, Smart Narrative, Decomposition Tree
- Dataset: [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Project Phases

### Phase 1 — Power BI Desktop Dashboard
- Loaded CSV using Power Query, transformed date columns and added Profit Margin column
- Created DAX measures: Total Sales, Total Profit, Total Orders, Profit Margin %
- Built interactive dashboard with KPI cards, bar/line/pie charts, US map, and customer table
- Added slicers for Region, Year, Category, Sub-Category, Segment

### Phase 2 — Microsoft Fabric (End-to-End)
- Created a Fabric workspace and Lakehouse
- Uploaded CSV to Lakehouse and loaded as Delta table
- Transformed data using Dataflow Gen2 (Power Query in the cloud)
- Built Semantic Model with DAX measures
- Created Power BI report connected to Fabric Lakehouse
- Published dashboard to Fabric workspace

### Phase 3 — AI Business Insights Dashboard
- Smart Narrative — auto-generated executive summary of key metrics
- Q&A Visual — natural language business question answering
- Key Influencers — AI analysis of what drives Total Profit
- Decomposition Tree — drill-down analysis by Category, Region, Segment

## Dashboard Metrics
- Total Sales: $2.30M
- Total Profit: $286.40K
- Total Orders: 5.01K
- Profit Margin: 12.47%

## Key Insights
- Technology is the highest revenue and profit category ($836K sales, $145K profit)
- West region leads with 31.58% of total sales
- November is the highest-performing month
- Discount rate is a key influencer of profit (identified by AI Key Influencers visual)
- South region underperforms with only 17.05% of total sales

## Dashboard Previews
- Power BI Desktop: `PowerBI/PowerBI_Dashboard.png`
- Microsoft Fabric: `Fabric/Superstore_Analytics_Report.pdf`
- AI Insights: `Fabric/Superstore_Analytics_Report.pdf`
