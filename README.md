# 🛒 Supermarket Sales Data Analysis
![Dashboard](https://github.com/user-attachments/assets/eb2c6886-e643-450d-b5ad-e6c92703fe97)


A complete end-to-end data analytics project focused on uncovering business insights from a regional supermarket chain. The project explores sales data across 10 stores, 20 products, 20 sales representatives, and 4 product categories, spanning from **April 2021 to February 2023**.

---

## 📁 Dataset Summary

The dataset was provided as an Excel workbook consisting of four sheets:
- **Sales Data**: Transaction-level data with `StoreID`, `RepID`, `ProductID`, `Date`, `Discount%`, `UnitPrice`, `Quantity`, and `Region`.
- **Stores Data**: Store metadata including `Region` and `Date of Opening`.
- **Products Data**: Product-level attributes such as `Category`, `Subcategory`, `Brand`, and `Cost Price`.
- **Sales Reps Data**: Details like `RepID`, `Join Date`, `Status`, and `Store Assignment`.

---

## 📊 Dashboard Plots & What They Convey

### 🔹 1. Monthly Sales by Region
- Highlights **seasonal trends** and **regional peaks**.
- Example: North peaks in **December**, South in **May**, East in **June**, and West in **March**.

### 🔹 2. Sales vs. Profit by Category
- **Toys** outperform others in profitability.
- **Home & Kitchen** shows high sales but relatively lower profit margins.

### 🔹 3. Sales Contribution by Subcategory
- Most sales come from:
  - `Home & Kitchen` → Furniture
  - `Toys` → Outdoor and Board Games

### 🔹 4. Rep Performance (Sales per Day)
- Measures normalized sales performance by calculating daily average per rep.
- Best performers: **Rep 205, 207, 219**

### 🔹 5. Product Profitability
- Visual ranking of products by **total profit over time**.
- Top 5: Products 307, 311, 317, 301, 319 (Home & Kitchen, Toys)
- Bottom 5: Products 302, 308, 315, 316, 320 and others in the same categories.

### 🔹 6. Avg. Monthly Sales of Bottom Products
- Year-wise normalized plot shows **Product 315** improving, while others show **declining demand**.

### 🔹 7. Store Sales Since Opening
- Evaluates **store performance over time**.
- **Store 107 and 109**, opened in 2022, compete well with older stores.

### 🔹 8. Discount vs. Sales Regionally (2022)
- North: Strong **positive response** to discounting.
- East: Only 1 store (103) - discount effect unclear.
- West: Store 109 responds well.
- South: **Weak correlation** between discount and sales.

---

## 💡 Key Insights

- 🧊 **Winter months (Nov–Jan)** are strongest in terms of sales, especially in the **North**.
- 🏆 **Rep 204 and Rep 205** are sales drivers, particularly in Store 109.
- 💰 **Toys** and **Home & Kitchen** categories dominate both revenue and profit — expanding SKUs in these areas could be strategic.
- ⚠️ Underperforming products (like 302, 308, 316, 320) should be reviewed or discontinued.
- 📍 Regional pricing strategy works — especially **discount-driven pricing in North and West**.

---

## 📌 Tools Used
- Microsoft Excel
- Power Pivot / Data Model
- Pivot Charts, Calculated Fields, Measures
- Data Cleaning and Normalization Techniques

---

## 📈 Business Applications
- Sales performance benchmarking
- SKU optimization
- Regional strategy planning
- Rep-level incentive design
- Inventory trimming for loss-making products

---

## ✅ Conclusion
The project delivers actionable insights into sales behavior, rep performance, product profitability, and regional trends,  all derived from transactional sales data. It aids in both **strategic decision-making** and **operational optimization** for supermarket chains.

---

**Created by:** Yog Gupta  
📅 **Data Range:** April 2021 - February 2023  
📌 **Regions Analyzed:** North, South, East, West

---

