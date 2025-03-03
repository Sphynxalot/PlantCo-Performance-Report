# PlantCo-Performance-Report

## 🚀 Overview  
This Power BI dashboard analyzes **plant sales data**, helping to track performance across **products, accounts, and locations**. The interactive visualizations provide insights into **sales trends, profitability, and year-over-year growth**.  

---

## 📂 Dataset  

The dataset consists of **three tables** stored in an Excel file:  

### **📦 Plant_FACT** (Sales Transactions)  
- `Product_id`  
- `Sales_USD`  
- `Quantity`  
- `Price_USD`  
- `COGS_USD`  
- `Date_Time`  
- `Account_id`  

### **🏢 Accounts** (Customer Details)  
- `country_code`  
- `Account`  
- `Master_id`  
- `Account_id`  
- `latitude`  
- `longitude`  
- `country`  
- `Postal_code`  
- `street_name`  
- `Street_number`  

### **🌿 Plant_Hierarchy** (Product Categorization)  
- `Product_Family`  
- `Product_Family_Id`  
- `Product_Group`  
- `Product_Group_id`  
- `Product_Name`  
- `Product_Name_id`  
- `Product_Size`  
- `Product_Type`  

---

## 🎯 Key Features  

### ✅ **Dynamic Slicers & Filters**  
- **Quantity, Sales, and Gross Profit slicers** dynamically update all visuals.  
- **Year dropdown** to filter data by specific years.  

### ✅ **Key Metrics Cards**  
- **YTD (Year-to-Date)**  
- **PYTD (Prior Year-to-Date)**  
- **YTD vs PYTD Change**  
- **Gross Profit % (GP%)**  
> *(All values update based on slicer selection.)*  

### ✅ **Interactive Charts**  
📊 **Treemap** → Bottom 10 **YTD vs PYTD by Country**  
📉 **Waterfall Chart** → **YTD vs PYTD breakdown** by **Month, Country, and Product**  
   - 📌 **Drill-down enabled** for deeper insights.  
📊 **Stacked Bar Chart** → **YTD vs PYTD per month by Product Type**  
📈 **Scatter Chart** → **Account Profitability Segmentation**  
   - **X-axis:** GP%  
   - **Y-axis:** Selected metric (Gross Profit, Quantity, or Sales)  

---

## 🔗 How to Use  
1️⃣ **Download the files** from this repository.  
2️⃣ **Open `Plant_Sales_Dashboard.pbix`** in **Power BI Desktop**.  
3️⃣ **Explore the interactive visuals** using slicers and filters.  
4️⃣ *(Optional)* **Connect your own dataset** by ensuring the schema matches.  

---

## 🛠 Tools Used  
- **📊 Power BI** – Data visualization and dashboard creation  
- **📂 Excel** – Data storage and preprocessing  
- **🔣 DAX (Data Analysis Expressions)** – Custom calculations  

---

## 🚀 Future Improvements  
- Add **forecasting models** for future sales trends.  
- Integrate **advanced DAX measures** for further data segmentation.  

---

## 📞 Contact Information  
📌 **Created by:** *Kyron Holbrook*  
📧 **Email:** *holbrookkyron@gmail.com*  
🔗 **Portfolio/GitHub:** [Sphynxalot](https://github.com/Sphynxalot) 
🔗 **LinkedIn:** [Kyron Holbrook](https://www.linkedin.com/in/kyron-holbrook/) 

---
