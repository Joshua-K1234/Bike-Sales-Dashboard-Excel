# Bike-Sales-Dashboard-Excel

![Bike Sales Dashboard](image-link-here)

## Overview
This Excel project analyzes bike sales data using pivot tables and slicers to create an interactive dashboard. The dashboard helps visualize key trends based on customer demographics and sales patterns.

## Data Cleaning & Transformations
- Removed all duplicate rows where rows were exactly the same (26 rows removed).
- Standardized marital status and gender columns by replacing abbreviations (e.g., "M" → "Married", "F" → "Female") with full titles for clarity.
- Changed data type of 'Income' to currency and decreased decimals.
- Added an "Age Brackets" column to categorize ages into defined groups for better analysis.
- Standardized distance values by converting "10+ Miles" to "More than 10 miles" for consistency.

## Pivot Tables
1. **Purchased Bike by Age Groups:**  
   - Analyzed the likelihood of purchasing a bike across different age groups.
   - Visualized the distribution of bike purchases (Yes/No) for each age group.

2. **Purchased Bike by Distance of Commute:**  
   - Examined the relationship between the distance of commute and bike purchases.
   - Grouped commute distances into categories by miles to identify trends.

3. **Purchased Bike by Average Income by Gender:**  
   - Compared the average income of customers who purchased a bike (Yes/No) across genders.
   - Highlighted income disparities and their impact on purchasing decisions.

## Dashboard Features
- **Slicers:** Three slicers were added to allow users to filter data across all pivot tables by:
  - **Region**
  - **Marital Status**
  - **Education Level**
- The slicers ensure that all tables update dynamically for easy data exploration.

## How to Use
1. Open the Excel file.
2. Interact with the slicers to filter the data.
3. Analyze the trends and insights displayed on the dashboard.
