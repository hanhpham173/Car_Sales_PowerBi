# 🚗 Car Sales Dashboard - Power BI Project

## 📊 Overview  
This Power BI project presents an **interactive and dynamic Car Sales Dashboard** designed to visualize and monitor key sales metrics. The dashboard enables users to explore trends in car sales, identify growth opportunities, analyze customer preferences, and support **data-driven decision-making** for car dealerships.

---

## 🎯 Project Objective  
The goal of this project is to design and develop a dynamic **Car Sales Dashboard using Power BI**. The dashboard visualizes **critical KPIs** related to car sales, providing actionable insights to support strategic decisions, performance tracking, and identification of key market trends.

---

## 🔄 Process  

### 1. **Data Preparation**  
- Loaded raw sales data into Power BI  
- Cleaned and transformed data using **Power Query Editor**  
- Structured the data model by establishing relationships across tables  
- Created **calculated columns** and **DAX measures** for KPI tracking  

### 2. **KPI Calculation**  
Used **DAX** to calculate:  
- **Year-to-Date (YTD)**  
- **Month-to-Date (MTD)**  
- **Year-over-Year (YOY)** growth  
- **Previous Year (PY)** comparisons  
- Developed measures for dynamic filtering, conditional formatting, and slicers  

### 3. **Visualization Creation**  
Created various visual components, including:  
- KPI Cards  
- Line Charts  
- Pie Charts  
- Maps  
- Tables (summary and detailed)  

### 4. **Dashboard Design**  
- Organized visuals into a clear, intuitive layout  
- Added slicers, custom tooltips, and a filter pane for enhanced interactivity  

---

## 🗃️ Data Modeling  

![Data Model Screenshot](https://raw.githubusercontent.com/hanhpham173/Car_Sales_PowerBi/70ec5e2f8ee74f73d8a0f7ee5fd0dba52d9ff09a/sc1.JPG)

The dataset was structured into the following five tables:  
- **Customers**: Customer ID, Name, Gender, Annual Income  
- **Region**: Region ID, Dealer Region  
- **Dealers**: Dealer ID, Dealer Name, Dealer No, Phone  
- **Car**: Car ID, Model, Body Style, Colour, Company, Engine, Price, Transmission  
- **Fact_Car**: Transaction data including Car ID, Customer ID, Dealer ID, Price, Date, Region  

---

## 📈 Dashboard Highlights  

![Dashboard Screenshot](https://raw.githubusercontent.com/hanhpham173/Car_Sales_PowerBi/11dcc94f5f3c7a56563312d9558a17b16188cffb/sc2.JPG)  
![Dashboard Screenshot](https://raw.githubusercontent.com/hanhpham173/Car_Sales_PowerBi/d45728ea2ccb2feddf2657869709600a9269fbd8/sc3.JPG)

### 🔢 Total Sales Metrics  
- **YTD Total Sales**: $371.19M (+23.59% YoY)  
- **MTD Total Sales**: $54.28M  

### 💰 Average Price Analysis  
- **YTD Avg Price**: $27.99K (↓0.79% YoY)  
- **MTD Avg Price**: $28.26K  

### 🚗 Cars Sold  
- **YTD**: 13.26K cars sold (+24.57% YoY)  
- **MTD**: 1.92K cars sold  

### 📅 Weekly Sales Trends  
- Line chart showing weekly YTD performance (2022–2023)  

### 🚙 Sales by Car Body Style  
- SUVs lead with nearly **$100M in sales**  

### 🎨 Sales by Car Colour  
- "Pale White" is the top-performing colour (**47.02%** share)  

### 🌍 Sales by Region (Map View)  
- **Austin**: highest units sold (2,296)  
- **Pasco**: lowest units sold (1,749)  

### 🏢 Sales by Company  
- **Chevrolet**: 1,043 units | $27.11M in revenue  

### 📋 Detailed Sales Table  
- Transaction-level data showing car model, body style, region, date, customer, dealer, and amount  

---

## 💡 Key Insights & Recommendations  

- **Capitalize on High-Performing Regions**: Increase efforts in Austin  
- **Focus on High-Demand Body Styles**: SUVs and Sedans perform well  
- **Optimize Pricing Strategies**: Monitor sensitivity and offer time-limited discounts  
- **Improve Low-Performing Regions**: Investigate factors in areas like Greenville  
- **Leverage Colour Preferences**: Promote "Pale White" and "Black"  
- **Strengthen Dealer Relationships**: Collaborate with top-selling brands like Chevrolet and Ford  
- **Segment Customer Base**: Use demographic data for personalized marketing  

---

## ✅ Conclusion  
This Power BI project demonstrates strong proficiency in:  
- **Data Transformation & Modeling**  
- **DAX Measures & KPI Calculation**  
- **Dashboard UI/UX Design**  

The final dashboard provides a comprehensive, interactive experience that supports **informed business decisions** and showcases **best practices in Power BI development**.

---

## 🛠️ Tools Used  
- Power BI Desktop  
- Power Query  
- DAX (Data Analysis Expressions)  
