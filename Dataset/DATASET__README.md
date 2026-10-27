# 🍕 Domino’s Pizza Nigeria - Dataset Documentation

This directory contains the sales, target, and branch data used for the **Domino’s Pizza Nigeria Sales Performance & Business Intelligence Analysis** project.

---

## 📁 Dataset Files Overview

| File Name | Description | Rows / Records | Key Columns |
| :--- | :--- | :--- | :--- |
| **`Sales-Data.csv`** | Primary transactional sales data across all branches | 5,000 records | `S/N`, `Date`, `Branch`, `Pizza Sold`, `Price`, `Quantity`, `Time`, `Time Range` |
| **`Branch-Data.csv`** | Store branch locations, coordinates, and branch managers | 5 branches | `Branch`, `Longitude`, `Lattitude`, `Manager` |
| **`Daily-Sales-Target.csv`** | Day-by-day sales benchmark target in Nigerian Naira (₦) | 13 days | `Day`, `Target` |
| **`Sales-Target.csv`** | Target sales revenue set for individual pizza products | 16 products | `Pizza`, `Sales Target` |

---

## 📊 Data Dictionary

### 1. `Sales-Data.csv`
- **`S/N`**: Serial / Transaction identifier.
- **`Date`**: Date of the transaction (December 2015 period).
- **`Branch`**: Store branch name (e.g., Ibadan, Ikoyi, Gbagada, Lekki, Surulere).
- **`Pizza Sold`**: Name / type of pizza purchased (e.g., Hot Pepperoni Feast, BBQ Chicken).
- **`Price`**: Unit price per item in Nigerian Naira (₦).
- **`Quantity`**: Number of pizzas ordered in the transaction.
- **`Time`**: Exact timestamp of the order.
- **`Time Range`**: Categorical time band of the order.

### 2. `Branch-Data.csv`
- **`Branch`**: Branch name.
- **`Longitude` & `Lattitude`**: Geographic coordinates for map visuals in Power BI.
- **`Manager`**: Name of the branch manager responsible for store operations.

### 3. `Daily-Sales-Target.csv`
- **`Day`**: Date corresponding to the operational day.
- **`Target`**: Projected revenue target for each individual date.

### 4. `Sales-Target.csv`
- **`Pizza`**: Specific pizza product variety.
- **`Sales Target`**: Benchmark revenue goal for the specific pizza item.

---

## 🎯 Use Case in Analysis & Dashboard
- **Descriptive Analytics**: Assessing total sales, units sold, and average ticket size vs. daily/product targets.
- **Diagnostic Analytics**: Comparing branch performance and product profitability gaps.
- **Predictive Analytics**: Forecasting revenue momentum for future planning.

---

## 🤝 Collaboration & Contact

Feel free to collaborate, suggest improvements, or discuss data analytics and BI projects!

- **Author:** Sojib Chandra Roy
- **📧 Email:** [rcsojib.cse1@gmail.com](mailto:rcsojib.cse1@gmail.com)
- **📞 Phone / WhatsApp:** [+8801312026018](tel:01312026018)
- **Role:** Data Analyst / BI Enthusiast
