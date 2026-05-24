# 📱 MobileX — Mobile Sales Dashboard

An interactive Power BI dashboard analyzing mobile phone sales datato track revenue, top-selling brands, regional performance,
and monthly sales trends.

---

## 📊 Dashboard Preview

<img width="1000" height="555" alt="Screenshot (1016)" src="https://github.com/user-attachments/assets/c958c386-d88f-49ea-bebc-0c9edaa67eed" />

---

## 📌 Project Overview

| Detail | Info |
|--------|------|
| Project Name | MobileX |
| Tool | Power BI Desktop |
| Domain | Retail / Consumer Electronics |
| Type | Sales Performance Dashboard |
| Dataset | Mobile Phone Sales Data |

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — Dashboard design and visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Custom KPI measures and calculations
- **Data Modeling** — Table relationships and schema design

---

## 📐 DAX Measures Created

```dax
Transaction = COUNTROWS(Sales_Data)

Total Quantity = SUM(Sales_Data[Units Sold])

Total Sales = SUMX(Sales_Data,Sales_Data[Units Sold]*Sales_Data[Price Per Unit])

Average = AVERAGE(Sales_Data[Price Per Unit])
```
---

## 🧹 Data Cleaning Steps (Power Query)

- Removed duplicate and null entries
- Standardized brand names and city spellings
- Created Month Name and Year columns from date
- Corrected data types for price and quantity columns
- Filtered out test/invalid entries

---

## 💡 Dashboard Features

- ✅ KPI Cards — Total Sales, Units Sold, Profit, Avg Price
- ✅ Bar Chart — Sales by Brand
- ✅ Map Visual — Revenue by City/Region
- ✅ Line Chart — Monthly Sales Trend
- ✅ Donut Chart — Sales share by Brand
- ✅ Slicers — Filter by Brand, Month, City

---

## 👩‍💻 About Me

**[Anu Jangid]**
Aspiring Data Analyst | Power BI | SQL | Excel

🔗 [LinkedIn](linkedin.com/in/anu-jangid-726564328)
📧 [email@gmail.com](anujangid2902@gmail.com)
🐙 [GitHub](https://github.com/AnuTech-01)

---

## ⭐ Star this repo if you liked the project!
