# 📊 PowerPivot Data Extraction & Modeling  

This project demonstrates how to use **Power Query and PowerPivot** to build a scalable data model, integrate multiple sales datasets, and generate actionable insights through DAX measures and star schema design.  

---

## 🎯 Project Overview  
**Business Problem:** Sales managers needed a unified view of multi‑year transaction data to analyze performance by product, region, and channel. Manual reporting was fragmented and error‑prone, making it difficult to identify trends and optimize strategy.  

This project covers:  
- Importing and consolidating raw sales data into the data model.  
- Designing a **star schema** with lookup tables for product, region, and channel.  
- Creating implicit and explicit measures using DAX.  
- Automating refreshes as new data files are added.  

---

## 🛠️ Process & Techniques  
1. **Data Import & Consolidation**  
   - Loaded 8 CSV sales transaction tables (2011–2018, 8,000+ rows).  
   - Used Power Query to append files into one consolidated dataset.  
   - Applied locale functions to standardize date formats.  
   - Created connections and loaded into the data model (scalable to 8M+ rows).  

2. **Data Modeling**  
   - Built a **star schema** with three lookup tables:  
     - Channel (Channel ID, Channel Name)  
     - Region (Region ID, Region Name)  
     - Product (Product ID, Product, Category, Price)  
   - Established relationships between fact and dimension tables.  

3. **DAX Measures**  
   - Number of Transactions  
   - Annual Quantity Sold  
   - Average Quantity per Transaction  

4. **Automation**  
   - Added 2019 and 2020 sales files into the folder.  
   - Refreshed queries to automatically update the consolidated dataset.  

---

## 📊 Key Insights  
- **Regional trends:**  
- **Channel performance:**  
- **Product mix:**   
- **Scalability:** 
---

## ✅ Recommendations  
- **Channel strategy:**
- **Regional expansion:**   
- **Product optimization:**  
- **Data governance:** 
---

## 🛠️ Tools & Skills  
- Power Query for data extraction, cleaning, and consolidation  
- PowerPivot for star schema modeling and relationships  
- DAX for custom measures and advanced calculations  
- ETL automation via folder imports and refresh workflows  
- Large‑scale data handling (millions of rows) in Excel’s data model  

---

💡 *This project demonstrates how fragmented sales data can be transformed into a unified, scalable model, enabling accurate reporting and strategic decision‑making across products, regions, and channels.*  