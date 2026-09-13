# Bike Sales Analysis Dashboard (Excel)

## Executive Summary:

A bike retailer wanted to know which customers to target with marketing spend, but had no clear view of who actually buys bikes. Using Excel, I cleaned a 1,000-row customer dataset, built pivot tables to analyze purchase behavior across demographics, and created an interactive dashboard with slicers so stakeholders can self-serve the answers. The analysis found that commute distance, car ownership, and age predict bike purchases far more strongly than income, and I recommend the business retarget its marketing around commuters and car-light households rather than high earners.

### Business Problem:

The retailer needed to know which customer segments convert best so marketing spend isn't wasted. Specifically: does income predict who buys a bike, or are lifestyle factors like commute and car ownership more important? And how do age, region, and marital status factor in? The goal was a dashboard stakeholders could filter themselves, without an analyst re-running reports.

<img width="955" height="637" alt="Screenshot 2026-09-13 152129" src="https://github.com/user-attachments/assets/bd64dc2f-df0c-4970-9483-88097240ccd1" />

### Methodology:

1. Cleaned the raw dataset in a working sheet: removed duplicates and standardized shorthand codes (e.g., M/S, M/F) into readable labels.
2. Engineered an Age Brackets column with nested IF formulas to segment customers into Adolescent, Middle Age, and Old.
3. Built three pivot tables and charts to analyze purchases by income, age bracket, and commute distance.
4. Designed a Dashboard sheet with a styled headline and all three charts on one screen.
5. Added slicers (Marital Status, Region, Education) connected across all pivot tables for real-time, self-service filtering.

### Skills:

Excel: Data cleaning, nested IF formulas, PivotTables, PivotCharts, dashboard design, slicers linked across multiple pivot tables

### Results & Business Recommendation:

The dashboard shows purchase rate isn't driven by income the way stakeholders assumed. Customers within 0-1 miles of work buy at ~55%, dropping to ~30% at 10+ miles. Customers with 0 cars buy at ~61%, falling as car count rises. Middle-aged customers (31-54) convert at ~55%, versus ~31-35% for younger and older groups. Meanwhile, average income for buyers vs. non-buyers barely differs across genders, and the Pacific region outconverts North America (~59% vs. ~43%) despite similar income levels.

Because proximity, car ownership, and age are the strongest signals, I recommend the business:

1. Target marketing at commuters within 1-2 miles of workplaces rather than by income bracket.
2. Focus campaigns on the 31-54 age group with messaging around convenience and health, not affordability.
3. Position bikes as a car alternative for low car-ownership households.
4. Investigate why North America underperforms the Pacific region despite similar customer income profiles.

I believe these changes will focus marketing spend on the segments most likely to convert, and the dashboard gives the sales team a way to explore any segment on their own going forward.
