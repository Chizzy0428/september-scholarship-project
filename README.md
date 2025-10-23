
# 🛒 Sample Superstore Data Analysis – Power BI Project

## 📘 Project Overview

The **Sample Superstore Data Analysis** project is a comprehensive business intelligence report created using **Power BI**. The project aims to analyze the performance of a retail company, *Sample Superstore*, across various dimensions such as **sales**, **profitability**, **customer segments**, **regions**, and **product categories**.

Through data cleaning, modeling, and visualization, the dashboard provides actionable insights to help business stakeholders make data-driven decisions that improve profitability and operational efficiency.

---

## 🎯 Objectives

The main goals of this analysis were to:

1. Identify **high-performing regions, categories, and customer segments**.
2. Analyze **sales and profit trends** over time.
3. Discover **low-profit or loss-making areas** that need attention.
4. Understand the **relationship between discount strategies and profitability**.
5. Provide **interactive visuals** for management to explore insights dynamically.

---

## 📊 Tools & Technologies Used

| Tool                                | Purpose                                                             |
| ----------------------------------- | ------------------------------------------------------------------- |
| **Power BI Desktop**                | Data modeling, DAX calculations, and interactive dashboard creation |
| **Microsoft Excel**                 | Data preprocessing and initial exploration                          |
| **Power Query**                     | Data cleaning, transformation, and merging                          |
| **DAX (Data Analysis Expressions)** | Calculations for KPIs and measures                                  |
| **Sample Superstore Dataset**       | Source dataset provided by Tableau/Power BI community               |

---

## 🧾 Dataset Description

The dataset contains detailed transactional data from a retail store with the following key fields:

| Column                              | Description                                          |
| ----------------------------------- | ---------------------------------------------------- |
| **Order ID**                        | Unique identifier for each order                     |
| **Order Date / Ship Date**          | Dates of purchase and shipment                       |
| **Customer Name / Segment**         | Information about customers and their market segment |
| **Country / Region / State / City** | Geographic information                               |
| **Product Category / Sub-Category** | Product classification                               |
| **Sales**                           | Revenue generated from each order                    |
| **Quantity**                        | Units sold                                           |
| **Discount**                        | Discount percentage applied                          |
| **Profit**                          | Net profit from each order                           |

---

## 🧹 Data Cleaning & Preparation

Data cleaning and preparation were done using **Power Query** in Power BI. The following steps were applied:

* Removed duplicate records and irrelevant columns.
* Standardized date formats and data types.
* Handled missing values and inconsistent entries.
* Extracted **Year**, **Month**, and **Quarter** from the Order Date.
* Created **calculated columns** and **measures** for analysis:

  * Total Sales = SUM(Sales)
  * Total Profit = SUM(Profit)
  * Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))
  * Discount Impact = [Calculated via correlation between Discount & Profit]
  * Sales Growth = [YoY% change using DAX]

---

## 📈 Dashboard Features

The Power BI dashboard is divided into **four main pages**, each providing a unique perspective of the business:

### 1. **Executive Summary**

* Key KPIs: Total Sales, Profit, Quantity, Average Discount, Profit Margin
* Year-over-Year trend of Sales and Profit
* Top 5 States by Sales and Profit
* Category-wise performance summary

### 2. **Regional Analysis**

* Map visualization of Sales and Profit by Region and State
* Regional contribution to total revenue
* Filters for Region, State, and City

### 3. **Product Performance**

* Category and Sub-Category performance matrix
* Most and least profitable products
* Discount vs. Profit scatter analysis

### 4. **Customer & Segment Insights**

* Customer segmentation by profitability
* Segment-wise Sales and Profit trends
* Customer retention and loyalty indicators

---

## 🧮 Key Insights

Some of the major insights derived from the analysis include:

* **The West region** consistently drives the highest sales and profit.
* **Technology** is the most profitable category, while **Furniture** shows low margins due to heavy discounts.
* Excessive discounts in certain sub-categories negatively affect profit.
* **Corporate and Consumer segments** contribute the majority of revenue.
* Seasonal spikes in sales are observed during the **end of the year** (holiday season).

---

## 💡 Recommendations

Based on the insights, the following recommendations were made:

1. **Reduce discounts** in underperforming product categories to improve profit margins.
2. **Increase marketing efforts** in regions with high potential but low sales (e.g., Central region).
3. Focus on **Technology category** expansion due to its consistent profitability.
4. Explore **loyalty programs** for high-value customer segments.
5. **Optimize logistics** in regions with high shipping costs to boost net profit.

---

## 📁 Project Structure

```
Sample_Superstore_PowerBI/
│
├── Dataset/
│   └── Sample_Superstore.csv
│
├── PowerBI_Report/
│   └── Sample_Superstore_Analysis.pbix
│
├── Screenshots/
│   ├── Dashboard_Overview.png
│   
│
└── README.md
```

---

## 🧠 Skills Demonstrated

* Data Cleaning and Transformation in Power Query
* Data Modeling and Relationship Management
* DAX for KPI and Metric Calculation
* Power BI Visualization Design
* Business Insights and Storytelling with Data
* Dashboard Interactivity (Slicers, Filters, Drillthroughs)



## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Connect or refresh the data if needed.
4. Explore the dashboard interactively using filters and slicers.

---

## 🧾 Conclusion

This project demonstrates the complete **end-to-end Power BI workflow**—from raw data to actionable insights. It showcases strong analytical and visualization skills and serves as a model for **retail sales performance analysis**.

---

## 👩‍💻 Author

**Name:** Chizaram Nwabuisi
**Role:** Data Analyst | Power BI Developer | AI Enthusiast
**LinkedIn:** [linkedin.com/in/chizaram-nwabuisi](#)
**GitHub:** [github.com/Chizzy0428](#)
