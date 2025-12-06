# 📊 PowerPivot Portfolio Project (Merged)

## 🎯 Project Overview  
**Business Problem:** Sales and product teams needed consistent, unified reporting across multiple years, categories, regions, and channels. Without proper calendar tables, star schema modeling, and advanced DAX measures, analysis was fragmented and limited to raw transaction dates.  

This project demonstrates how Power Query and PowerPivot can be combined to:  
- Build calendar tables for time intelligence  
- Consolidate multi‑year sales datasets into a scalable star schema  
- Apply DAX iterator and time intelligence functions for advanced reporting  
- Automate refreshes and maintain a recruiter‑ready workflow  

---

## 🛠️ Process & Techniques  

### 1. Data Import & Consolidation  
- Loaded 8 CSV sales transaction tables (2011–2018, 8,000+ rows)  
- Used Power Query to append files into one consolidated dataset  
- Standardized date formats and created connections scalable to millions of rows  

### 2. Calendar Table Creation  
- Generated calendar tables using Excel sheet functions, Power Query, and PowerPivot  
- Linked calendar table to sales fact tables via the `Date` column  
- Enabled time intelligence functions (YTD, QTD, MTD)  

### 3. Data Modeling  
- Designed a **star schema** with lookup tables: Product, Region, Channel  
- Established relationships between fact and dimension tables  

### 4. DAX Measures & Iterator Functions  
- Created implicit and explicit measures in PowerPivot  
- Applied iterator functions (`SUMX`, `COUNTX`, `AVERAGEX`) for advanced calculations  
- Managed row and filter context for accurate reporting  

### 5. Automation  
- Added new sales files (2019, 2020) into the folder  
- Refreshed queries to automatically update the consolidated dataset  

---

## 🛠️ Tools & Skills  
- Excel sheet functions for calendar generation  
- Power Query for extraction, cleaning, and consolidation  
- PowerPivot for star schema modeling and relationships  
- DAX iterator and time intelligence functions (`SUMX`, `COUNTX`, `AVERAGEX`, `DATESYTD`, `DATESQTD`, `DATESMTD`)  
- ETL automation via folder imports and refresh workflows  
- Large‑scale data handling (millions of rows) in Excel’s data model  

---

## 💡 Insights  
1. **2018 revenue** was the highest, showing recovery from the 2017 decline  
2. **2017 revenue** dropped across all categories and regions  
3. **Bikes** consistently reported the highest revenue, while **components** were lowest; accessories and clothing performed below average  
4. **Alex, Cairo, and Giza** reported high revenue, while Canal, Delta, and Sanal were average  
5. **Alex’s revenue** is declining gradually, while **Canal’s revenue** is improving  
6. **Door‑to‑door channel** reported the lowest revenue, with no bike sales; clothing performed best in this channel  
7. **March and December** had the highest turnover, with Q3 and Q4 outperforming other quarters  

---

## 🎯 Recommendations  
1. Investigate factors behind the **2017 sales drop** (internal vs. external) and continue improving 2018 strategies  
2. Conduct a **market product analysis** on components to understand low sales compared to strong bike sales  
3. Consider introducing **online sales channels** to replace or complement door‑to‑door sales  
4. Study the **decline in Alex’s revenue** by comparing strategies with Canal, which shows gradual improvement  
5. Implement **strategic marketing** for clothing and accessories, e.g., bundling discounted packages with bike sales  

---

💡 *This merged README demonstrates how Power Query, PowerPivot, and DAX together enable scalable, time‑intelligent analysis, transforming fragmented sales data into actionable insights and recommendations for management.*