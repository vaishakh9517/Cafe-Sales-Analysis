# Café-Sales-Analysis

This repository contains the deliverables and documentation for a **Cafe Sales Data Analysis** project. The aim is to analyze transactional sales data from a café to uncover customer preferences, payment trends, and item performance across locations, enabling data-driven business decisions.

---

## 📁 Project Structure

/Cafe-Sales-Analysis/
│
├── MySQL_Database_Scripts/ # SQL scripts used for data cleaning and merging
│ └── data_merge.sql
│
├── PowerBI_Reports/ # Power BI files and dashboards
│ └── CafeSalesDashboard.pbix
│
└── README.md # This file


---

## 📊 Project Overview

### 🔍 Objective
Investigate café sales transactions to identify:
- Popular items and underperformers
- Payment method trends
- Sales performance by location (in-store vs takeaway)

### 🧮 Data Summary
- **Source:** Multiple CSV files merged into a MySQL database
- **Key Features:**
  - `Item` – Type of food or beverage sold (e.g., Coffee, Salad, Cake)
  - `Quantity` – Number of units sold per transaction
  - `Price Per Unit` – Cost of a single unit
  - `Total Spent` – Total cost per transaction
  - `Payment Method` – Mode of payment (Cash, Credit Card, Digital Wallet)
  - `Location` – In-store or Takeaway
  - `Transaction Date` – Date of sale

---

## 🛠️ Procedure Followed

1. **Data Loading:**  
   Merged CSV files into a unified MySQL database for efficient cleaning and querying.

2. **Data Cleaning:**  
   - Removed irrelevant and empty columns.  
   - Checked and handled null values.  
   - Standardized item names, payment methods, and location entries for consistency.

3. **Data Transformation:**  
   - Aggregated sales by item.  
   - Grouped data by payment method and location.  
   - Converted transaction dates into proper date formats.

4. **Data Visualization:**  
   Created interactive dashboards and charts in Power BI, including:  
   - Bar and column charts (item popularity)  
   - Line graphs (sales trends over time)  
   - Doughnut charts (payment method share)  
   - KPI cards (total revenue, average sales)

---

## 📈 Key Findings

- **Top-Selling Items:**  
  Salads led sales, significantly outperforming other items. Sandwiches, Smoothies, and Juices followed but didn’t exceed 15K in total sales.

- **Payment Trends:**  
  Credit Cards were the most common payment method (though some transactions lacked payment data). Cash and Digital Wallets were also popular.  
  *Recommendation:* Promote Digital Wallet use with targeted cashback offers to boost adoption.

- **Sales by Location:**  
  Takeaway sales dominated over in-store orders, indicating a preference for takeaway or potential dine-in limitations.

- **Underperforming Items:**  
  Tea and Cookies had the lowest sales and transaction counts.  
  *Recommendation:* Consider promotional strategies or phased removal to improve profitability.

---

## 📌 Conclusion

The café can improve profitability by:
- Prioritizing stock and promotions around high-demand items like Salads and Sandwiches.
- Encouraging Digital Wallet payments via incentives.
- Enhancing the dine-in experience to attract convenience-focused customers.
- Reviewing low-performing items to reduce waste.

Implementing these data-driven strategies will help boost overall efficiency and revenue.

---

## 🙋‍♂️ About Me

**Vaishakh K**  
Aspiring Data Analyst | Excel | MySQL | Python | Tableau | Power BI 
[LinkedIn](https://www.linkedin.com/in/vaishakh-k-0b2bb8202/) • [Portfolio](https://github.com/vaishakh9517)


