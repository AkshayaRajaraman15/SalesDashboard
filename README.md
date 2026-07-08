# SalesDashboard
1. Project Overview
The Sales Dashboard project provides a unified platform for analyzing customer insights, sales performance, and representative efficiency. It consolidates KPIs, trends, and visualizations into three interactive pages: Summary, Customer Insights, and Sales Performance.

With Row-Level Security (RLS), each sales representative will only see data relevant to their accounts, customers, and performance metrics, ensuring confidentiality and personalized insights.

2. Objectives
Deliver a comprehensive view of sales performance across regions, customers, and representatives.

Provide customer behavior insights (repeat vs. new customers, acquisition trends, engagement vs. orders).

Enable representative-level analysis with RLS so each rep sees only their own data.

Ensure filter-driven interactivity (Year, Month, Region, Customer, Sales Rep).

Support scalable reporting for future datasets and business expansion.

3. Scope of Work
Page 1 – Summary
KPIs:

% Repeat Customers

% New Customers

Total Revenue

Average Order Value

Navigation buttons: Customer Insight, Sales Performance

Filters: Year, Month, Region, Customer, Sales Rep

Purpose: Provide a high-level snapshot of overall business health.

Page 2 – Customer Insights
Visuals:

Average Order Value per Segment (Yearly trend)

Customer Acquisition by Region (2013–2017)

Customer Growth by Year (line chart)

Website Engagement vs. Orders (scatter plot)

Purpose: Highlight customer behavior patterns, acquisition trends, and engagement impact on sales.

Page 3 – Sales Performance
Visuals:

Avg Sales by Representative

Top 10 Customers (bar chart)

Total Revenue by Region

Monthly Revenue Trend (2014–2017)

Account Distribution per Representative

Sales by Representative (ranking chart)

Purpose: Provide representative-level performance analysis and regional revenue distribution.

Row-Level Security (RLS) Implementation
Roles Defined:

Sales Representative: Sees only their accounts, customers, and performance metrics.

Executive: Full visibility across all regions and representatives.

Mapping Table:

Columns: LoginEmail, SalesRepID, Role


Testing: Validate access for reps, managers, and executives to ensure no unauthorized data leakage.

4. Deliverables
Interactive Power BI dashboard with 3 pages.

Configured RLS roles in Power BI Service.

Drill-through and bookmark navigation between pages.

Exportable reports for stakeholders.

Documentation of KPIs, metrics, data sources, and RLS logic.

5. Out of Scope
Predictive modeling or advanced AI-driven forecasting (future phase).

Integration with external CRM systems (unless specified later).

Real-time streaming data (current scope is batch/ETL-driven).

6. Stakeholders
Primary Users: Sales Representatives, Sales Managers, Executives.

Data Owners: BI Team, Data Engineering Team.

Support Teams: IT Infrastructure, Power BI Admins.

7. Success Criteria

Reduction in manual reporting effort by 30%.

Improved visibility into customer acquisition and representative performance.

Secure RLS implementation ensuring reps see only their data.

Actionable insights leading to measurable revenue growth.
