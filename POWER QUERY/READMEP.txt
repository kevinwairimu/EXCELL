# ⚡ Power Query ETL Projects  
Welcome to my **Power Query ETL Repository**!  
This space demonstrates how to use Power Query to **extract, transform, and load (ETL)** data from multiple sources, ensuring clean, structured, and analysis‑ready datasets.  

---

## 📂 Project Structure
- `Web Data/` → Importing and cleaning tables from online sources.  
- `Text & CSV/` → Handling raw text/CSV files, replacing missing values, and converting data types.  
- `Excel Sources/` → Loading and transforming data from external and current worksheets.  
- `Combine & Merge/` → Combining tables, merging datasets, and appending files for automation.  
- `Advanced Transformations/` → Grouping, unpivoting, transposing, and text/date/time functions.  

---

## 🛠️ Tools & Skills
- Power Query (ETL workflows)  
- Data type conversions (text, number, date, currency)  
- Append & Merge queries  
- Data cleaning (remove errors, replace values, handle nulls)  
- Automation with query connections  
- Advanced transformations (Group By, Unpivot, Transpose, Fill Down/Up)  

---

## 🎯 Purpose
This repository showcases how I leverage Power Query to:  
- Extract data from diverse sources (web, text, Excel, folders).  
- Transform messy datasets into structured, error‑free tables.  
- Automate repetitive cleaning steps for efficiency.  
- Load clean data into Excel for dashboards and analysis.  

---

## 🚀 ETL Workflows

### 1. Get Data from Web
- **Source 1:** [Highest‑Grossing Films](https://en.wikipedia.org/wiki/List_of_highest-grossing_films)  
  - Use *Get Data → From Web*  
  - Select the desired table  
  - Remove unwanted columns (e.g., reference column)  
  - Clean currency fields: replace `$` with blank, then change type to *Number*  

- **Source 2:** [Kenya Counties by Population](https://en.wikipedia.org/wiki/List_of_counties_of_Kenya_by_population)  
  - Import table, remove unnecessary fields, confirm data types  

---

### 2. Get Data from Text/CSV
- Use *Get Data → From Text/CSV*  
- Replace missing values (`...`) with `null`  
- Convert data types appropriately  
- Example: Sales of June text file → clean and load  
- For July → simply change the data source, steps replicate automatically  

---

### 3. Get Data from Excel Worksheets
- **External Worksheet:**  
  - Import *Sales Data July 2018.xlsx*  
  - Select sheet, remove empty rows, fix data types  

- **Current Worksheet:**  
  - Use *Get Data → From Table/Range*  
  - Load from Excel table or non‑table range  

---

### 4. Combine Tables (Automation & Efficiency)
- Region‑wise sales data (West, East, North, South)  
- Load each into Power Query, add a custom column for region  
- Create connections, then **Append Queries** to combine  
- Alternative: use `=Excel.CurrentWorksheet()` to dynamically reference tables  

---

### 5. Merge Tables
- Example:  
  - Table 1: Sales data (Date, Item, Sales Rep, Quantity, Price, Commission)  
  - Table 2: Item & Product ID  
  - Table 3: Sales Rep & Region  
- Load each as a connection, then **Merge Queries** on common columns  
- Build a unified dataset for analysis  

---

### 6. Append Files from Different Workbooks
- Import East, West, and North Excel sheets  
- Format and create connections for each  
- Append connections into one consolidated dataset  

---

### 7. Combine Excel Files from a Folder
- Use *Get Data → From Folder*  
- Filter by extension if mixed files exist  
- Use `Excel.Workbook([Content])` to extract tables  
- Expand and filter by *Kind = Table*  
- Combine and clean tables (sort, filter, replace errors, split/merge columns)  

---

## 🔧 Advanced Transformations
- **Merge Columns with Delimiter:** Add custom column → `Column1 & " - " & Column2`  
- **Fill Down/Up:** Propagate values across rows  
- **Transpose:** Convert rows into columns  
- **Group By:** Aggregate sales data by item or salesperson  
- **Unpivot:** Convert pivoted data back into normalized format  
- **Locale Handling:** Adjust date formats (e.g., `dd-mm-yy` vs `mm-dd-yy`)  
- **Date & Time Functions:**  
  - Calculate age/difference between dates  
  - Extract year, month, day  
  - Parse datetime into usable values  
- **Text Functions:**  
  - Extract length, first/last characters  
  - Get text before/after/between delimiters  

---

💡 *These ETL projects highlight  ability to transform raw data into structured, analysis‑ready datasets using Power Query.*  