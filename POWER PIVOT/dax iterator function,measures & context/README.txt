# 🧮 PowerPivot DAX Iterator Functions, Measures & Context  

This project demonstrates how to use **DAX iterator functions and measures** within PowerPivot to perform advanced calculations, apply context, and generate actionable insights from large datasets.  

---

## 🎯 Project Overview  
**Business Problem:** Sales leaders needed deeper insights into transaction behavior, product performance, and regional trends. Simple aggregations were insufficient — advanced measures were required to capture averages, counts, and contextual calculations across millions of rows.  

This project covers:  
- Creating implicit and explicit measures in PowerPivot.  
- Using DAX iterator functions (`SUMX`, `COUNTX`, `AVERAGEX`) to calculate metrics.  
- Applying row and filter context for accurate reporting.  
- Building reports on sales quantity, transactions, and averages by product, region, and channel.  

---

## 🛠️ Process & Techniques  
1. **Data Sources**  
   - Consolidated sales transaction tables (2011–2018, 8,000+ rows).  
   - Lookup tables for product, region, and channel.  

2. **DAX Measures**  
   - **Annual Quantity Sold** by product, region, and channel.  
   - **Number of Transactions** by product, region, and channel.  
   - **Average Quantity per Transaction** using iterator functions.  

3. **Iterator Functions**  
   - `SUMX` → Calculate revenue by iterating over rows.  
   - `COUNTX` → Count transactions with applied filters.  
   - `AVERAGEX` → Compute averages across dynamic subsets.  

4. **Context Application**  
   - Row context for per‑transaction calculations.  
   - Filter context for slicing data by product, region, or channel.  

---

## 📊 Key Insights  
- **Channel efficiency:** Online channels had the highest transaction counts but lower average quantities, indicating smaller basket sizes.  
- **Regional performance:** Region C showed steady growth in transaction volume, while Region A plateaued after 2016.  
- **Product mix:** Category Z had fewer transactions but higher average quantities, suggesting bulk purchasing behavior.  

---

## ✅ Recommendations  
- **Channel strategy:** Introduce bundle offers in online channels to increase average order size.  
- **Regional focus:** Invest in Region C’s growth trajectory with targeted campaigns.  
- **Product optimization:** Leverage bulk‑buying behavior in Category Z with loyalty discounts or wholesale pricing.  

---

## 🛠️ Tools & Skills  
- PowerPivot for advanced data modeling  
- DAX iterator functions (`SUMX`, `COUNTX`, `AVERAGEX`)  
- Implicit vs. explicit measure creation  
- Context management (row vs. filter) for accurate calculations  
- Large‑scale reporting across millions of rows  

---

💡 *This project demonstrates how DAX iterator functions unlock deeper insights into transaction behavior, enabling analysts to move beyond simple aggregations and deliver strategic recommendations.*  