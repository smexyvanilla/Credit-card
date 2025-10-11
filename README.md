# Credit-card
This interactive Power BI Dashboard provides deep insights into credit card customer behavior and transaction performance.
It tracks key financial metrics such as Revenue, Total Interest, Income, Transaction Volume, and Customer Satisfaction Score (CSS), while analyzing customer demographics, spending behavior, and card usage types.

The dashboard is designed to assist financial analysts and management teams in understanding customer profiles, identifying high-value segments, and optimizing card strategies.

1.Data Cleaning & Preparation:
Removed duplicate and null values to maintain data accuracy.
Replaced missing data using:
Mean for continuous numerical data
Median for skewed numerical distributions
Mode for categorical variables
Removed unnecessary decimal values and formatted percentages for consistency.
Standardized numerical values and ensured uniform data types.
Performed data transformation using Power Query for easier analysis.

2.Data Visualization
Main KPIs:
Total Revenue: 55.4M
Total Interest: 7.9M
Total Income: 576M
Customer Satisfaction Score (CSS): 3.19
Transaction Count: 657K

3.Key Visuals:
Revenue by Week: Line chart showing weekly revenue trends throughout 2023.
Quarterly Revenue & Transaction Count: Combined column-line chart comparing Q1–Q4 performance.
Revenue by Age Group: Highlights spending patterns of customers aged 30–60+.
Revenue by Gender: Gender-based spending distribution.
Revenue by Income Group: Visualizes contribution by Low, Medium, and High income categories.
Revenue by Education Level: Graduate and Post-Graduate customers show the highest contribution.
Revenue by Marital Status and Dependents: Understands family-based spending trends.
Revenue by Customer Job: Shows key earning segments like Businessmen, Govt, Blue-collar, and Self-employed customers.
Revenue by Card Category: Analysis of Platinum, Gold, Silver, and Blue cards.
Revenue by Usage Type: Compares transactions done via Swipe, Chip, and Online methods.
Customer Acquisition Cost: Evaluates acquisition costs across card categories.
Revenue by Expenditure Type: Breaks down spending into Bills, Fuel, Grocery, Entertainment, Travel, etc.

4. Interactivity:
Interactive slicers and filters were added to enhance user exploration:
Filter by Quarter (Q1–Q4)
Filter by Gender (Male/Female)
Filter by Income Group (Low/Medium/High)
Filter by Card Category (Blue/Silver/Gold/Platinum)
Filter by Week_Start_Date for time-based analysis
Users can dynamically filter and compare results across different segments, quarters, or demographics

5.Design and Layout:
Clean and structured layout separating KPI cards, charts, and tables.
Consistent color-coded theme (shades of blue and yellow) for visual contrast.
Enhanced readability using rounded visuals, grid layout, and tooltips.
Data labels enabled on charts for easy interpretation.
Dashboard sections grouped logically — Customer Overview, Transaction Insights, and Revenue Breakdown.

6.Dashboard Insights:
Blue and Silver cards generate the majority of total revenue.
Graduates and Self-employed customers are top contributors to spending.
High-income customers contribute over 60% of total revenue.
Swipe transactions dominate usage type, followed by Chip transactions.
Revenue peaks in Q3, with a noticeable decline in Q4.
Retirees and Govt employees show lower activity compared to Businessmen.

7.Tools & Techniques Used
Tool:
Microsoft Power BI Desktop
Techniques:
Data cleaning and transformation using Power Query Editor
Business logic creation using DAX (Data Analysis Expressions)
Dynamic KPI cards, bar charts, line charts, and tables
Interactive slicers for enhanced user control
Data modeling to establish relationships between customer and transaction tables

