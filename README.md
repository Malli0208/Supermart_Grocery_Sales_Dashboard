# Supermart_Grocery_Sales_Dashboard

📌 Project Overview
The Supermart Grocery Sales Dashboard is an Excel-based data analytics project designed to help management understand overall sales, profitability, product performance, discounts, and geographic performance.
The project transforms raw grocery sales data into KPIs, PivotTables, charts, and business insights that support data-driven decision-making.
The analysis is structured around four key business objectives:
1. Overall Sales Performance
2. Product Performance
3. Profit & Discount Analysis
4. Geographic Performance

🎯 Business Objective
The main objective of this project is to analyze grocery sales data and answer important business questions related to:
- Sales performance
- Profitability
- Product and sub-category performance
- Discount impact
- Geographic performance
The final Excel dashboard provides management with a simple view of important business metrics without requiring them to analyze the complete raw dataset.
🗂️ Dataset
The dataset contains grocery sales transactions with fields including:
- Order ID
- Customer Name
- Category
- Sub Category
- City
- Order Date
- Region
- Sales
- Discount
- Profit
- State
- Profit Margin
Data Preparation
Before analysis, the dataset was cleaned and prepared by:
- Removing duplicate records
- Checking and handling blank values
- Standardizing date formats
- Formatting Sales and Profit as numeric values
- Formatting Discount as a percentage
- Creating a Profit Margin field
- Creating a cleaned date field to support time-based analysis
🎯 Objectives & Analysis
1️⃣ Objective 1 — Overall Sales Performance
Business Question
How is the overall grocery business performing?
Analysis Performed
- Total Sales
- Total Profit
- Sales by Product Category
- Monthly Sales Trend
- Sales by Region
Key Results
KPI	Result
Total Sales	₹14,956,982
Total Profit	₹3,747,121.20
Overall Profit Margin	~25%

Key Insights
- The business generated approximately ₹14.96 million in total sales.
- Total profit was approximately ₹3.75 million.
- The overall profit margin was approximately 25%.
- Sales fluctuate over time rather than following a completely constant trend.
- Product categories and regions contribute differently to overall sales performance.
2️⃣ Objective 2 — Product Performance
Business Question
Which products and categories are driving sales and profit?
Analysis Performed
- Category-wise Sales
- Sub-category-wise Sales
- Sales vs Profit by Sub-category
- Profit Margin comparison
Top Selling Sub-Categories
Sub-Category	Sales
Health Drinks	₹1,051,439
Soft Drinks	₹1,033,874
Cookies	₹768,213
Breads & Buns	₹742,586
Noodles	₹735,435

Key Insights
- Health Drinks generated the highest sales among the analyzed sub-categories.
- Soft Drinks were the second-highest sales contributor.
- High sales do not always translate into the highest profitability.
- Spices, Atta & Flour, and Masalas showed comparatively lower profit margins despite generating significant sales.
This highlights the importance of analyzing profitability alongside revenue.

3️⃣ Objective 3 — Profit & Discount Analysis
Business Question
How are discounts and profit related to business performance?
Analysis Performed
- Profit by Category
- Profit by Region
- Discount vs Profit analysis
- Profit Margin analysis
Key Insight
The Discount vs Profit analysis showed that profit fluctuates across different discount levels rather than consistently decreasing as discounts increase.
Therefore, the analysis does not show a strong visual relationship between discount and profit.
Business Interpretation
Discount percentage alone does not appear to fully explain profitability.
Other factors such as:
- Product mix
- Sales volume
- Pricing
- Costs
- Customer demand
may also influence profit performance.

4️⃣ Objective 4 — Geographic Performance
Business Question
Which locations are contributing most to the business?
Analysis Performed
- State and City analysis
- City-wise Sales
- City-wise Profit
- City-wise Profit Margin
- Sales vs Profit by City
Geographic Observation
The dataset contains one state, so state-level comparison is limited.
Therefore, the analysis focuses primarily on city-level performance.
Top Cities by Sales
City	Sales	Profit Margin
Kanyakumari	₹706,764	24.27%
Vellore	₹676,550	25.61%
Bodi	₹667,177	25.96%
Tirunelveli	₹659,812	24.80%
Perambalur	₹659,738	26.27%

Key Insight
Kanyakumari generated the highest sales at approximately ₹706,764, but its profit margin of 24.27% was comparatively lower than several other high-sales cities.
This indicates an opportunity to investigate profitability in high-revenue locations.
📊 Dashboard Components
The Excel dashboard contains analysis using:
- 📌 KPI summaries
- 📊 Bar charts
- 📈 Line charts
- 📉 Combo charts
- 🔵 Discount vs Profit analysis
- 📋 PivotTables
- 📅 Monthly sales analysis
- 🏙️ City-level geographic analysis
🛠️ Tools & Technologies
Tool	Purpose
Microsoft Excel	Data analysis and dashboard
PivotTables	Aggregation and analysis
PivotCharts	Data visualization
Excel Formulas	KPI calculations
Conditional Formatting	Performance highlighting
Charts	Business insights

📐 Key Metrics
The project calculates and analyzes:
Sales
Total Sales = SUM(Sales)

Profit
Total Profit = SUM(Profit)

Profit Margin
Profit Margin = Profit / Sales

Average Discount
Average Discount = AVERAGE(Discount)

📁 Project Structure
Supermart-Grocery-Sales-Dashboard/
│
├── Supermart_Grocery_Sales_Dashboard.xlsx
│
├── README.md
│
└── Screenshots/
    ├── Dashboard.png
    ├── Objective1.png
    ├── Objective2.png
    ├── Objective3.png
    └── Objective4.png

💡 Key Business Insights
1. Overall Performance
The business generated approximately ₹14.96M in sales and ₹3.75M in profit, resulting in an overall profit margin of approximately 25%.
2. Product Performance
Health Drinks and Soft Drinks were among the strongest sales contributors.
3. Profitability
Some high-sales sub-categories have comparatively lower margins, particularly:
- Spices
- Atta & Flour
- Masalas
These areas may require further investigation into pricing, discounts, and costs.
4. Discount Impact
The analysis did not reveal a strong consistent relationship between discount percentage and profit.
5. Geographic Performance
Kanyakumari recorded the highest city-level sales, but its profit margin was comparatively lower than several other high-performing cities.
📈 Business Recommendations
Based on the analysis:
1. Focus on high-performing product categories to maintain strong revenue generation.
2. Investigate high-sales but relatively low-margin sub-categories.
3. Review pricing and discount strategies rather than assuming discounts alone drive lower profit.
4. Monitor high-revenue cities such as Kanyakumari for opportunities to improve margins.
5. Continue tracking monthly sales trends to identify stronger and weaker periods.
6. Analyze product-level costs and pricing in greater detail to understand the reasons behind margin differences.
🎓 Skills Demonstrated
This project demonstrates practical skills in:
- Data Cleaning
- Excel Data Analysis
- PivotTables
- PivotCharts
- KPI Development
- Business Analysis
- Profitability Analysis
- Sales Trend Analysis
- Geographic Analysis
- Data Visualization
- Business Insight Generation
- Dashboard Development
🏁 Conclusion
The Supermart Grocery Sales Dashboard converts raw transaction data into meaningful business insights using Microsoft Excel.
The analysis provides management with a clear understanding of sales, profit, product performance, discount behavior, and geographic performance.
The project demonstrates how Excel can be used not only for basic calculations, but also for structured business analysis and decision-making.
👨‍💻 Project Type
Data Analytics | Excel Dashboard | Business Intelligence
Tool: Microsoft Excel
Focus: Sales & Profit Analytics
Dataset: Supermart Grocery Sales Data
