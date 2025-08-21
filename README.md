# 📊 Sales & Customer Insights Dashboard (Power BI)

## 🔎 Overview  
This project showcases a **Power BI dashboard** designed to analyze sales performance, product profitability, and customer behavior.  
The dataset was restructured from a flat file into a **star schema model** with multiple fact and dimension tables, enabling efficient queries and scalable analysis.  
In addition, **10+ custom DAX measures** (including YTD/MTD metrics, Profit Margin, CLV, and Shipment KPIs) were created to provide deeper insights.  

The goal is to deliver actionable insights for executives and stakeholders, supporting data-driven decisions in areas such as **regional sales trends, product category performance, and customer segmentation**.  

---

## 📂 Dataset  
- **Source:** [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
- The original dataset was provided as a **single flat table** (`superstore.csv`).  
- For professional reporting and scalability, the data was restructured into a **star schema** with proper **dimension and fact tables**.  

---

## 🛠 Data Modeling & Measures  
- Built a **star schema data model** to improve performance and analytical flexibility.  
- Established relationships between:  
  - **Fact Table**: FactSales  
  - **Dimension Tables**: DimProducts, DimCustomers, DimRegions, DimDate  
- Developed **10+ DAX measures** for advanced analytics, including:  
  - **Total Sales**, **Total Profit**, **Profit Margin**  
  - **Year-to-Date (YTD)** and **Month-to-Date (MTD)** metrics  
  - **Customer Lifetime Value (CLV)**  
  - **Shipment Status metrics**  

> ⚡ By restructuring the dataset and creating reusable DAX measures, the dashboard provides **faster performance, better scalability, and deeper insights** compared to working with a single flat table.  

---

## 📊 Dashboard Pages  

### 1. Executive Sales Overview  
- High-level KPIs (Sales, Profit, Quantity)  
- Regional sales performance  
- Monthly sales and profit trends  

![Executive Overview](images/sales.png)  

---

### 2. Product Performance Overview  
- Sales & profit by category and subcategory  
- Top 10 best-performing products  
- Profit margin comparison across categories  

![Product Performance](images/product.png)  

---

### 3. Customer & Market Overview  
- Customer segmentation and CLV (Customer Lifetime Value)  
- Geographic analysis (city & state-level insights)  
- Shipment analysis  

![Customer Overview](images/customer.png)  

---

## 📈 Key Insights  
- Top-performing categories accounted for a significant share of total profit, highlighting opportunities for product prioritization.  
- Regional sales analysis revealed underperforming markets, indicating potential areas for strategic improvement.  
- CLV analysis emphasized the importance of repeat customers in driving sustainable revenue.  
- Shipment metrics uncovered patterns that can be optimized to improve customer satisfaction and operational efficiency.  

---

## 🛠 Tools & Skills Used  
- **Power BI**: Data Modeling, DAX, Power Query, Visualization  
- **Data Cleaning & Transformation**  
- **Business Insights & Dashboard Design**  

---

## 🌍 Live Dashboard  
You can explore the interactive dashboard here:  

[🔗 View Dashboard on Power BI](https://app.powerbi.com/view?r=eyJrIjoiYWE2NjBlNjUtNDUzOS00ZDM3LWIxZmMtMjQyMjE5OTI1YjhiIiwidCI6ImExMzM2ODc5LWFiOWMtNDhiYi1iMWFjLWE2OWNhZTJlOGRmZSIsImMiOjl9)  

⚠️ *Note: The dashboard is shared publicly for demonstration purposes only. Dataset is non-confidential and sourced from Kaggle.*  

---

## 🚀 How to Use  
- Interact with the report directly via the **live link** (slicers, filters, drill-downs available).  
- Or download the `.pbix` file from the repository and open it in **Power BI Desktop** for offline exploration.  

---

**Author:** [Ersin Tepegöz](https://www.linkedin.com/in/tepegozersin/)  
