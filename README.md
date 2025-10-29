# 📊 Audio Sales Data Analysis – Buyhatke Business Analyst Assignment

**Author:** Vansh Angaria  
**Tool:** Microsoft Excel / Google Sheets  
**Date:** October 2025  

---

## 🧭 Overview
Analysis of e-commerce audio product sales (Amazon dataset) to identify key insights, brand performance, and pricing synergy.  
Deliverables include data cleaning, pivot-based analysis, and a dynamic dashboard.

---

## 📂 Dataset
**File:** `data.csv`  
**Key Columns:**  
`date`, `user`, `product_name`, `brand`, `level2_name` `category`, `price`, `city`, `state`

---

## 🧹 Data Preparation
- Removed ₹ and commas → numeric `Price_Num`
- Added:
  - `Date_Clean` – formatted date  
  - `Price_Bucket` – (`<=500`, `501-1000`, `1001-2000`, `2001-5000`, `5001+`)
- Converted to Excel Table → `Table_Raw`

---

## 📈 Analysis Summary
| Focus | Method | Insight |
|--------|--------|---------|
| **Brand Revenue** | Pivot (Brand × Sum of Price) | SONY & JBL lead revenue |
| **Category Share** | Pivot (Category × Sum) | Headsets = 54% of sales |
| **Sales Trend** | Grouped by month | Festive spike in Oct |
| **Top Products** | Filter top 10 | SONY WH & JBL Tune top models |
| **Repeat Buyers** | Count of User >1 | 12% loyalty rate |
| **Price Segments** | Bucket vs Category | ₹1001–2000 most active |
| **Synergy Map** | Brand × Category heatmap | Cross-category strength for SONY/JBL |

---

## 💡 KPIs
| Metric | Value |
|---------|--------|
| 💰 Total Revenue | ₹10.16 Cr |
| 👥 Unique Users | 3.23 L |
| 🎧 Products Sold | 20,644 |
| 💹 Avg Price | ₹3,624 |
| 🏆 Top Brand | SONY |
| 🔁 Repeat Buyer % | ~12% |

---

## 🧩 Dashboard Highlights
- KPI cards (revenue, users, products, avg price, brand)
- Visuals: Column, Donut, Line, Treemap charts  
- Slicers: Brand, Category, Date  
- Theme: Blue (#007BFF), Teal, White  
- Insight Tagline: *“Synergy between sound, savings, and sales.”*

---

## 📘 Deliverables
1. `Business_Analyst_Assignment_VanshAngaria.xlsx` – Cleaned data + Dashboard  
2. `README.md` – Project summary  
3. (Optional) `Buyhatke_CabCompare_Strategy.pptx` – Marketing strategy deck
