🚗 Car Sales Dashboard - Power BI Project
📊 Overview
This Power BI project presents an interactive and dynamic Car Sales Dashboard designed to visualize and monitor key sales metrics. The dashboard enables users to explore trends in car sales, identify growth opportunities, analyze customer preferences, and support data-driven decision-making for car dealerships.

🎯 Project Objective
The objective of this project is to design and develop a dynamic and interactive Car Sales Dashboard using Power BI. This dashboard visualizes critical KPIs related to car sales, providing actionable insights to aid in strategic decision-making, performance tracking, and identifying key market trends.

🔄 Process
1. Data Preparation
Loaded sales data into Power BI.

Cleaned and transformed data using Power Query Editor.

Created a structured data model by building relationships across relevant tables.

Developed calculated columns and measures using DAX.

2. KPI Calculation
Utilized DAX to calculate:

Year-to-Date (YTD)

Month-to-Date (MTD)

Year-over-Year (YOY) growth

Previous Year (PY) comparisons

Developed measures for dynamic filtering, conditional formatting, and slicers.

3. Visualization Creation
Built a variety of visuals including:

KPI Cards

Line Charts

Pie Charts

Maps

Tables

Integrated summary and detail views for holistic insights.

4. Dashboard Design
Designed a clean, intuitive layout for easy navigation.

Included interactive slicers, tooltips, and a filter pane for enhanced user experience.

🗃️ Data Modeling

![Dashboard Screenshot](https://raw.githubusercontent.com/hanhpham173/Car_Sales_PowerBi/70ec5e2f8ee74f73d8a0f7ee5fd0dba52d9ff09a/sc1.JPG)

The dataset was structured into the following five tables:

Customers: Customer ID, Name, Gender, Annual Income

Region: Region ID, Dealer Region

Dealers: Dealer ID, Dealer Name, Dealer No, Phone

Car: Car ID, Model, Body Style, Colour, Company, Engine, Price, Transmission

Fact_Car: Transaction data including Car ID, Customer ID, Dealer ID, Price, Date, Region

📈 Dashboard Highlights

https://github.com/hanhpham173/Car_Sales_PowerBi/blob/11dcc94f5f3c7a56563312d9558a17b16188cffb/sc2.JPG

Total Sales Metrics

YTD Total Sales: $371.19M (+23.59% YoY)

MTD Total Sales: $54.28M

Average Price Analysis

YTD Avg Price: $27.99K (↓0.79% YoY)

MTD Avg Price: $28.26K

Cars Sold

YTD: 13.26K cars sold (+24.57% YoY)

MTD: 1.92K cars sold

Weekly Sales Trends

Line chart showcasing weekly YTD performance from 2022 to 2023

Sales by Car Body Style

SUVs lead with nearly $100M in sales

Sales by Car Colour

Pale White is the top-performing colour (47.02% share)

Sales by Region (Map View)

Austin has the highest units sold (2,296), Pasco the lowest (1,749)

Sales by Company

Chevrolet tops with 1,043 units and $27.11M in revenue

Detailed Sales Table

Shows sale-level data: car model, body style, region, date, customer, dealer, and amount

💡 Key Insights & Recommendations
Capitalize on High-Performing Regions: Boost efforts in Austin, the top sales region.

Focus on High-Demand Body Styles: SUVs and Sedans show strong performance.

Optimize Pricing Strategies: Monitor price sensitivity and offer time-limited discounts.

Improve Low-Performing Regions: Investigate factors behind lower sales in regions like Greenville.

Leverage Colour Preferences: Promote popular colours like Pale White and Black.

Strengthen Dealer Relationships: Chevrolet and Ford are leading brands — explore partnership enhancements.

Segment Customer Base: Use demographic insights for personalized marketing.

✅ Conclusion
This project showcases strong proficiency in Power BI, from data transformation and modeling to DAX calculations and dashboard design. The final dashboard delivers a comprehensive, interactive experience that supports informed decision-making for car dealerships and reflects best practices in data visualization.

🛠️ Tools Used
Power BI Desktop

DAX (Data Analysis Expressions)

Power Query
