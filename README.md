# E-Commerce Funnel & User Behavior Analysis

This repository contains a comprehensive analysis of user behavior and conversion patterns for a Direct-to-Consumer (D2C) e-commerce platform. The project focuses on identifying funnel drop-offs, segmentation insights, and potential revenue opportunities.

## Project Overview
- Analyze user sessions across an e-commerce funnel: from website visit to purchase completion.
- Identify stages with the highest drop-offs.
- Segment users based on channel, campaign type.
- Estimate stage-wise lost revenue opportunities.

## Notebook
The main analysis is available in this [Jupyter Notebook](https://github.com/sonasahakyan11/ecommerce-funnel-analysis/blob/main/User_Behavior_Conversion_Analysis.ipynb), which contains:
1. Data Loading & Initial Inspection
2. SQL-based Data Exploration & Cleaning
3. Funnel Analysis
4. User Segmentation
5. Python Behavioral Analysis & Visualizations
6. Marketing Performance Analysis
7. Revenue Opportunity Analysis (Stage-wise Lost Revenue)

## Tools & Technologies
- **SQL (SQLite)** – Data exploration, aggregation, and segmentation.
- **Python (Pandas, Matplotlib, NumPy)** – Behavioral analysis, visualizations, and revenue opportunity calculations.
- **Google Colab** – Interactive notebook environment.

## Key Insights
- Largest drop-off occurs between product view and cart addition (~65% of users do not add a viewed product to cart).
- Paid Ads drive the highest traffic, but Email channels show stronger conversion rates.
- Discount campaigns attract the most users; Influencer campaigns show higher engagement at the View → Cart stage.
- Stage-wise lost revenue indicates the most significant revenue opportunity lies in improving product page conversion (Viewed → Cart).

## Business Recommendations
- Optimize product pages: improve descriptions, images, and reviews.
- Simplify checkout forms and provide multiple payment options.
- Scale high-performing channels (Email, Organic) while improving Paid Ads targeting.
- Run A/B tests to evaluate improvements on funnel stages.

## Limitations
- Session-level data, not full multi-session user journeys.
- Simplified marketing attribution (one channel or campaign type per session).
- Behavioral signals such as time on page or product categories are not included.

## Future Work
- Cohort analysis for new vs returning users.
- Device-specific behavior analysis.
- Conversion rates for combinations of marketing channel and campaign type․
- A/B testing for product page and checkout optimizations.

