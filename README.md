# 📊 Sales Analytics & Business Performance Dashboard

## 📌 Project Overview

This project is a **client-style Sales Analytics and Business Performance Dashboard** developed using **Microsoft Power BI**.

The objective was to analyze sales data from multiple business dimensions and answer **20 business-focused questions** related to sales, profit, customers, payment methods, products, cities, regions, categories, and sales channels.

Instead of creating visuals randomly, I approached this project from a **Data Analyst's perspective** by treating each requirement as a business question and using data to identify meaningful insights.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Cleaning**
* **Data Analysis**
* **Data Visualization**
* **Business Intelligence**

---

## 📂 Dashboard Pages

The Power BI report contains **4 analytical pages**:

### 1️⃣ Overall Sales Analysis

Provides a high-level overview of the company's sales and profitability.

### 2️⃣ Channel Analysis

Analyzes sales and profitability across sales channels, customer demographics, age groups, and payment methods.

### 3️⃣ Payment & Deeper Analysis

Provides deeper analysis of payment methods, customer profitability, cities, and product performance.

### 4️⃣ Advanced Business Analysis

Combines **Region + Category + Channel** to identify the strongest business combinations.

---

# 📷 Dashboard Preview

> **Click any dashboard image to open the full-size version.**

## Page 1 — Overall Sales Analysis

[![Overall Sales Analysis](Dashboard/Page_1_Overall_Sales.png)](Dashboard/Page_1_Overall_Sales.png)

---

## Page 2 — Channel Analysis

[![Channel Analysis](Dashboard/Page_2_Channel_Analysis.png)](Dashboard/Page_2_Channel_Analysis.png)

---

## Page 3 — Payment & Deeper Analysis

[![Payment & Deeper Analysis](Dashboard/Page_3_Payment_Deeper_Analysis.png)](Dashboard/Page_3_Payment_Deeper_Analysis.png)

---

## Page 4 — Advanced Business Analysis

[![Advanced Business Analysis](Dashboard/Page_4_Advanced_Business_Analysis.png)](Dashboard/Page_4_Advanced_Business_Analysis.png)

---

# 📈 Key KPIs

| KPI                     |   Value |
| ----------------------- | ------: |
| **Total Sales**         | 222.08M |
| **Total Profit**        |  34.34M |
| **Total Orders**        |     20K |
| **Total Quantity Sold** |     45K |
| **Average Order Value** |  11.10K |

---

# 🎯 Business Questions

The dashboard was developed around **20 client-style business questions**.

### Overall Business Performance

1. What is the overall sales, profit, orders, and quantity sold?
2. How are total sales distributed across regions?
3. Which region generates the highest and lowest profit?
4. Which product category generates the highest and lowest sales?
5. Which product category generates the highest and lowest profit?
6. How have sales changed over time?

### Channel & Customer Analysis

7. Which sales channel generates the highest total sales?
8. Which sales channel generates the highest total profit?
9. Which sales channel has the highest profit margin?
10. How are sales distributed between male and female customers?
11. Which age group generates the highest and lowest sales?
12. Which age group has the highest and lowest Average Order Value?

### Payment & Customer Profitability

13. Which payment method generates the highest and lowest sales?
14. Which payment method generates the highest and lowest profit?
15. Which payment method has the highest and lowest profit margin?
16. Which age group generates the highest and lowest total profit?
17. Which age group has the highest and lowest profit margin?

### Advanced Analysis

18. Which city generates the highest and lowest sales among the selected Top 15 cities?
19. Which products generate the highest sales and profit?
20. Which Region + Category + Channel combination generates the highest sales and profit?

---

# 💡 Key Business Insights

### 🌍 Regional Performance

* **South** generated the highest regional sales at approximately **70M**.
* **South** also generated the highest regional profit at approximately **10.7M**.
* **East** recorded the lowest regional sales and profit.

### 🛍️ Category Performance

* **Electronics** was the strongest category.
* Electronics generated approximately **187M in sales**.
* Electronics generated approximately **29M in profit**.

### 📱 Channel Performance

* **Online** was the highest-performing channel by sales at approximately **100M**.
* Store generated approximately **69M**.
* Mobile App generated approximately **53M**.
* Online also generated the highest profit at approximately **15.7M**.

### 👥 Customer Analysis

* Female customers generated approximately **113M** in sales.
* Male customers generated approximately **109M**.
* The **56+ age group** generated the highest sales at approximately **49M**.
* The **36–45 age group** had the highest Average Order Value at approximately **11.6K**.
* The **56+ age group** generated the highest profit at approximately **7.6M**.
* The **46–55 age group** had the highest profit margin at approximately **15.84%**.

### 💳 Payment Method Analysis

* **UPI** generated the highest sales at approximately **93M**.
* UPI also generated the highest profit at approximately **14.6M**.
* UPI had the highest payment-method profit margin at approximately **15.77%**.
* Credit Card had the lowest payment-method profit margin at approximately **14.93%**.

### 🏙️ City Performance

Among the selected Top 15 cities:

* **Chandigarh** had the highest sales at approximately **17.4M**.
* **Patna** had the lowest sales at approximately **8.3M**.

### 📦 Product Performance

* **Laptop** was the strongest product by both sales and profit.
* Laptop generated approximately **131M in sales**.
* Laptop generated approximately **20.1M in profit**.
* Smartphone was the second-highest product by both sales and profit.

### 🔎 Combined Business Performance

The strongest combination identified in the analysis was:

**South → Electronics → Online**

* **Sales:** ₹26.27M
* **Profit:** ₹4.09M

This combination ranked highest for both sales and profit in the analysis.

---

# 📊 Analytical Approach

The project followed a structured business-analysis workflow:

```text
Business Questions
        ↓
Data Understanding
        ↓
Data Cleaning & Transformation
        ↓
Power Query
        ↓
DAX Measures & Calculations
        ↓
Data Visualization
        ↓
Business Analysis
        ↓
Insights & Recommendations
```

---

# 🧮 Key DAX Measures

### Total Sales

```DAX
Total Sales =
SUM('Sales Data'[Sales])
```

### Total Profit

```DAX
Total Profit =
SUM('Sales Data'[Profit])
```

### Total Orders

```DAX
Total Orders =
COUNT('Sales Data'[Order_ID])
```

### Total Quantity

```DAX
Total Quantity =
SUM('Sales Data'[Quantity])
```

### Average Order Value

```DAX
Average Order Value =
DIVIDE([Total Sales], [Total Orders], 0)
```

### Profit Margin

```DAX
Profit Margin =
DIVIDE([Total Profit], [Total Sales], 0)
```

---

# 📁 Repository Structure

```text
Sales-Analytics-PowerBI/
│
├── README.md
│
├── Sales_Analytics_Business_Performance_Dashboard.pbix
│
├── Dashboard/
│   ├── Page_1_Overall_Sales.png
│   ├── Page_2_Channel_Analysis.png
│   ├── Page_3_Payment_Deeper_Analysis.png
│   └── Page_4_Advanced_Business_Analysis.png
│
├── Dataset/
│   └── sales_data.csv
│
└── Documentation/
    └── Business_Questions.md
```

> **Note:** The dataset should only be uploaded if it is permitted for public distribution.

---

# 🎓 Skills Demonstrated

Through this project, I practiced and demonstrated:

* Business Requirement Analysis
* Data Cleaning
* Data Transformation
* Power Query
* DAX
* KPI Development
* Sales Analysis
* Profitability Analysis
* Customer Analysis
* Regional Analysis
* Product Analysis
* Channel Analysis
* Payment Method Analysis
* Age Group Analysis
* Data Visualization
* Interactive Dashboard Development
* Business Insight Generation

---

# 🚀 Project Outcome

This project helped me understand how a Data Analyst can move beyond simply creating charts and instead:

> **Translate business questions into analytical requirements, analyze data, identify patterns, and communicate actionable business insights through an interactive dashboard.**

---

# 👤 About Me

**Nagireddy Rakada Rupesh**

B.Tech 2026 Graduate | Aspiring Data Analyst

**Core Skills:**
`SQL` · `Excel` · `Power BI` · `Python` · `Data Analysis`

### Connect With Me

* 🔗 **LinkedIn:** [linkedin.com/in/rakada-rupesh](https://www.linkedin.com/in/rakada-rupesh)
* 💻 **GitHub:** [github.com/Rupesh-29](https://github.com/Rupesh-29)

---

⭐ **If you found this project useful, feel free to explore the repository and connect with me.**
