# 📅 PowerPivot Calendar Tables  

This project demonstrates how to create and integrate **Calendar Tables** using Excel sheet functions, Power Query, and PowerPivot. Calendar tables are essential for enabling **time intelligence functions**, bridging fact tables, and supporting date‑based classifications in advanced reporting.  

---

## 🎯 Project Overview  
**Business Problem:** Sales and product teams needed consistent time‑based reporting (yearly, quarterly, monthly) to track revenue trends. Without a calendar table, analysis was fragmented and limited to raw transaction dates.  

This project covers:  
- Building calendar tables using sheet functions, Power Query, and PowerPivot.  
- Integrating calendar tables into the data model.  
- Enabling time intelligence functions for advanced reporting.  
- Linking sales and product tables through the date column.  

---

## 🛠️ Process & Techniques  
1. **Data Sources**  
   - Sales table: `(ProductID, Date, Quantity, Revenue)` covering 3 years.  
   - Product table: `(ProductID, Product, Category)`.  

2. **Calendar Table Creation**  
   - Generated calendar tables using:  
     - Excel sheet functions.  
     - Power Query transformations.  
     - PowerPivot integration.  
   - Linked calendar table to the sales table via the `Date` column.  

3. **Analysis & Reporting**  
   - Revenue by category across **yearly, quarterly, and monthly** periods.  
   - Enabled time intelligence functions (YTD, QTD, MTD).  
   - Supported comparisons across multiple fact tables using the calendar bridge.  

---

## 📊 Key Insights  
- **Seasonality:** Revenue peaks consistently in Q4, suggesting strong holiday demand.  
- **Category trends:** Category A shows steady growth year‑over‑year, while Category B fluctuates seasonally.  
- **Granularity:** Monthly breakdown revealed short‑term dips masked in quarterly reporting.  

---

## ✅ Recommendations  
- **Inventory planning:** Increase stock levels ahead of Q4 to meet seasonal demand.  
- **Category strategy:** Invest in Category A’s growth trajectory while stabilizing Category B with targeted promotions.  
- **Reporting standardization:** Use calendar tables across all fact tables to ensure consistent time‑based analysis.  

---

## 🛠️ Tools & Skills  
- Excel sheet functions for basic calendar generation  
- Power Query for automated calendar creation and transformation  
- PowerPivot for integrating calendar tables into the data model  
- Time intelligence functions (YTD, QTD, MTD) for advanced reporting  
- Data modeling techniques for bridging multiple fact tables  

---

💡 *This project demonstrates how calendar tables unlock powerful time intelligence in PowerPivot, enabling consistent and actionable revenue analysis across categories and time periods.*  