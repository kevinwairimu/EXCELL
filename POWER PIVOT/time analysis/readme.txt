# 📊 Power Pivot Project: Time Intelligence Analysis

## 🔍 Business Problem
This project analyzes multi‑year sales performance across categories, regions, and channels using Power Pivot time intelligence functions. The objective is to uncover revenue trends, identify declines or growth patterns, and provide actionable recommendations for management.

## 🛠️ Tools & Techniques
- **Power Query** → Load and transform sales files, lookup tables, and calendar data  
- **Power Pivot** → Build data models and relationships  
- **DAX Time Intelligence Functions** → Perform yearly, quarterly, monthly, and cumulative revenue analyses  

## 📂 Data Sources
- **Sales Data**: Three years of sales stored in separate sheets (`AllSales`)  
- **Lookup Tables**: Region, channel, and product details  
- **Calendar Table**: Dates spanning 2016–2018, later extended to include 2019 sales  

## ⚙️ Setup Instructions
1. Start with an empty Excel worksheet  
2. Load all sales files into Power Query  
3. Add lookup tables (region, channel, product)  
4. Create and load a calendar table (2016–2018, extended to 2019)  
5. Build relationships in Power Pivot and refresh the data model  

## 📈 Analysis Approach
- **Yearly Revenue Analysis**: Categories, regions, and channels using time intelligence functions  
- **Quarterly & Monthly Analysis**: Revenue trends using the `DATEADD` function  
- **Running Revenue Analysis**: Cumulative revenue (monthly, quarterly, yearly) using `DATESMTD`, `DATESQTD`, and `DATESYTD`  

## 💡 Insights
1. **2018 revenue** was the highest, showing recovery from the 2017 decline  
2. **2017 revenue** dropped across all categories and regions  
3. **Bikes** consistently reported the highest revenue, while **components** were lowest; accessories and clothing performed below average  
4. **Alex, Cairo, and Giza** reported high revenue, while Canal, Delta, and Sanal were average  
5. **Alex’s revenue** is declining gradually, while **Canal’s revenue** is improving  
6. **Door‑to‑door channel** reported the lowest revenue, with no bike sales; clothing performed best in this channel  
7. **March and December** had the highest turnover, with Q3 and Q4 outperforming other quarters  

## 🎯 Recommendations
1. Investigate factors behind the **2017 sales drop** (internal vs. external) and continue improving 2018 strategies  
2. Conduct a **market product analysis** on components to understand low sales compared to strong bike sales  
3. Consider introducing **online sales channels** to replace or complement door‑to‑door sales  
4. Study the **decline in Alex’s revenue** by comparing strategies with Canal, which shows gradual improvement  
5. Implement **strategic marketing** for clothing and accessories, e.g., bundling discounted packages with bike sales  