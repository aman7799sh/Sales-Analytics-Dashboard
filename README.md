# Sales Analytics Dashboard

## Project Overview
Analyzed 50,000 rows of raw sales data to build an 
end-to-end Excel analytics solution — from data 
cleaning to interactive dashboard.

## Tools Used
Excel | Power Query | Pivot Tables | Conditional Formatting

## 1. Data Cleaning (Power Query)
- Fixed mixed date formats across Order Date & Ship Date
- Removed duplicate Order IDs and handled blank values
- Standardized text columns (Trim + Proper Case)
- Fixed wrong-scale Discount values (1.5 → 0.15)
- Standardized Return Status (6+ variations → Yes/No)
- Handled outliers and nulls in Profit column

## 2. Business Questions Answered
- Which region generates highest revenue?
- Which category has highest return rate?
- Who are top/bottom performing sales reps?
- What is the monthly sales trend (2021-2024)?
- How does discount affect profit margin?

## 3. KPIs Designed
| KPI | Value |
|---|---|
| Total Revenue | ₹73.25M |
| Total Profit | ₹31.43M |
| Profit Margin % | 42.91% |
| Avg Sale Value | ₹2,308.67 |
| Return Rate | 2.38% |

## 4. Pivot Tables Built (9 total)
- Region × Year (Sales, Profit, Margin%)
- Category × Sub-Category performance
- Segment × Ship Mode (AOV analysis)
- Sales Rep Leaderboard (Top/Bottom 10)
- Return Rate by Category × Ship Mode
- Seasonality analysis (Month × Year)

## 5. Advanced Analysis
- YoY Growth Rate using Pivot calculated fields
- Discount vs Profit correlation (Scatter chart)
- Return Rate Heatmap (Conditional Formatting)
- Seasonality Heatmap

## 6. Dashboard
Interactive dashboard with 4 dynamic slicers 
(Year, Region, Category, Segment) connected to 
all charts and KPI cards.

## Dashboard Preview
![Dashboard](dashboard_screenshot.png)
