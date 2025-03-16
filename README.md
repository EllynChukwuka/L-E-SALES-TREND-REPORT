# L & E SALES TREND REPORT
This analysis aims to assess sales trends, customer purchasing patterns, and product performance. By leveraging Excel tools, we identify key insights to optimize sales strategies and enhance business decision-making.
OUTLINE
Introduction
Story of Data
Data Splitting and Preprocessing
Pre-Analysis
In-Analysis
Post-Analysis and Insights
Data Visualizations & Charts
Recommendations and Observations
Conclusion
References & Appendices

2. INTRODUCTION
This report presents an analytical overview of sales data from L & E Minimart. The objective is to understand customer behavior, product performance, and sales trends using Microsoft Excel. The analysis follows these key sections:

Objective of the Project
This analysis aims to assess sales trends, customer purchasing patterns, and product performance. By leveraging Excel tools, we identify key insights to optimize sales strategies and enhance business decision-making.

Problem Being Addressed
What are the top-selling products and categories?
How do sales vary by city and branch?
Do customer demographics (gender, membership status) influence purchasing behavior?
What insights can be derived to improve business performance?
Key Dataset Used and Methodology
Datasets Used: “Sales” sheet containing transactions.
Excel Techniques Used: Pivot Tables, Filtering, Sorting, Data Validation, Conditional Formatting, and Data Visualization tools.

3. STORY OF DATA
Data Source
This dataset originates from L & E Minimart’s internal transaction records.

Data Collection Process
Data is recorded at the point of sale, capturing transaction details including branch, customer demographics, product information, and sales amounts.

Data Structure
Each row represents a transaction with key attributes:

Sales details: sale_id, branch, city
Customer details: customer_type, gender
Product details: product_name, product_category
Financials: unit_price, quantity, tax, total_price, reward_points
Important Features and Their Significance
Customer Type: Differentiates between members and non-members.
Product Category: Helps identify top-performing categories.
Branch & City: Essential for regional sales analysis.
Total Price & Quantity: Critical for revenue and inventory management.
Data Limitations or Biases
Potential missing or incorrect entries.
Data does not account for seasonal trends or external economic factors.

4. Data Splitting and Preprocessing
Data Cleaning
Removed duplicates and inconsistencies.
Checked for missing values in key columns.
Handling Missing Values
Used interpolation and logical approximations where needed.
Excluded rows with critical missing values affect the analysis.
Data Transformations
Created new variables (e.g., revenue per product, average purchase amount per customer type).
Standardized product categories for consistency.

Data Splitting
Dependent Variable: Total Price
Independent Variables: Product name, category, quantity, city, branch
Industry Context
Retail industry — focusing on consumer behavior and product performance.

Stakeholders
Sales and marketing teams
Inventory managers
Executive decision-makers
Value to the Industry
Understanding sales trends allows for better stock management, targeted marketing strategies, and improved customer engagement.

5. PRE-ANALYSIS
Identify Key Trends
Members tend to make larger purchases compared to non-members.
Certain product categories (e.g., Beverages, Personal Care) consistently outperform others.
Sales distribution varies significantly by city.
Potential Correlations
Higher reward points are often linked to higher total purchases.
Price elasticity affects customer purchasing behavior.
Initial Insights
Sales are concentrated in specific cities.
Some product categories drive higher revenue despite lower purchase volumes.

6. IN-ANALYSIS
Unconfirmed Insights
Does gender influence product preferences?
Are promotions significantly impacting purchasing patterns?
Recommendations
Consider targeted promotions based on membership and purchase history.
Optimize stock allocation to branches based on city-specific sales trends.
Analysis Techniques Used in Excel
Pivot Tables for product/category sales.
SUMIFS, AVERAGEIFS, and COUNTIFS for aggregated insights.
Conditional formatting for outlier detection.

7. Post-Analysis and Insights
Key Findings
Beverages and Personal Care products are best-sellers.
Members contribute a larger share of the revenue.
City-based sales trends highlight regional preferences.
Comparison with Initial Findings
Initial expectations about product demand were validated.
Sales variation across cities was more significant than assumed.

8. Data Visualizations & Charts
Charts and Graphs
Bar charts for product performance
Line graphs for sales trends over time
Pie charts for customer demographics
Dashboards
A consolidated dashboard displaying key sales KPIs.
Explanation of Visualizations
Trends by city and branch to guide regional marketing strategies.
High-performance product categories to inform inventory decisions.

9. Recommendations and Observations
1.Branch Performance

Branch A is the top-performing branch, driving the majority of sales.

Branch B has lower sales compared to Branch A, especially in Los Angeles.

New York and Chicago branches are consistently performing well, while Los Angeles is lagging. Branch A dominates sales, while Branch B underperforms, requiring intervention.

2. City-Wise Sales Trends

New York has the highest number of sales transactions, making it the most profitable location.

Chicago follows closely, suggesting strong customer demand.

Los Angeles has the lowest sales volume, which indicates weak customer engagement or competition.


3. Sales by Gender

Male customers account for a slightly higher percentage of sales.

However, female customers show a higher average spending per transaction.

Promotional strategies seem gender-neutral but could be optimized to target higher-spending customers.

4. Best-Selling Products

Shampoo is the top-selling product, indicating strong demand for personal care items.

Fruits (e.g., Apples) are also frequently purchased, showing stable demand for fresh produce.

Household products like Detergent rank high, reflecting daily necessity purchases.

5. Sales by Product Category

Personal Care, Fruits, and Household items generate the highest revenue.

Beverages and Stationery contribute less to total sales.

Certain categories underperform, indicating either low demand or lack of promotion.


Actionable Insights
Implement personalized promotions for members.
Expand inventory for top-selling product categories.

Recommendations

1. Boost Sales in Los Angeles (Branch B)

Issue: Los Angeles has lower sales compared to other cities.

Conduct a market survey to understand customer preferences and barriers to purchasing.

Increase brand visibility in Los Angeles through local advertisements, influencer partnerships, and digital marketing campaigns.

Run city-specific promotions, such as discounts exclusive to Los Angeles customers.

Introduce branch-exclusive loyalty rewards to encourage repeat visits.

Analyze product availability in Los Angeles and ensure high-demand products are well-stocked.

2. Target Female Customers with Premium Offers

Develop exclusive product bundles for women-focused items (e.g., skincare, personal care).

Offer discounts on premium products that appeal to female shoppers.

Partner with beauty/lifestyle influencers to promote high-end personal care and household products.

Highlight best-selling female-oriented products.


3. Optimize Inventory & Promotions for Best-Selling Products

Shampoo, Fruits, and Household items are top sellers and should be prioritized.

Ensure high stock levels of top-performing products to avoid shortages.

Create bundle deals, such as “Buy Shampoo & Conditioner together at 10% off.”

Run a limited-time promotion on bestsellers, such as “Weekend Sale: 15% off all Detergents!”


4. Improve Sales in Underperforming Categories (Stationery & Beverages)

Stationery and Beverages contribute less revenue.

Bundle stationery products with other items (e.g., “Back-to-School Pack: Notebooks + Pens at a Discount!”).

Run beverage promotions.

Improve product placement in stores to increase visibility and sales.

Consider seasonal demand for beverages and launch special limited-time flavors or promotions.

Optimizations or Business Decisions
Adjust pricing for price-sensitive products.
Enhance reward programs for high-value customers.
Unexpected Outcomes
Certain products underperform despite high expectations.
Some cities have an unexpectedly high volume of sales.

10. Conclusion
Key Learnings
Membership programs drive significant revenue.
Product category and pricing strategies impact purchasing behavior.
Sales trends vary greatly across different locations.
Limitations
The dataset does not include seasonal or promotional impact data.
Potential data entry errors could affect accuracy.
Future Research
Incorporate time-series forecasting for better inventory planning.
Explore external factors such as competitor pricing and promotions.
References & Appendices
Data Source: L & E Minimart Sales Database
Excel Functions Used: SUMIFS, AVERAGEIFS, Pivot Tables
[L & E MINIMART.xlsx](https://github.com/user-attachments/files/19269135/L.E.MINIMART.xlsx)
<img width="927" alt="L    E DASHBOARD" src="https://github.com/user-attachments/assets/654a8768-89ef-45ec-a1de-e140dfa51f87" />

