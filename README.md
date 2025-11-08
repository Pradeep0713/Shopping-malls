# 🛍️ Customer Shopping Behavior Analysis (SQL + Power BI)

## 🧾 Project Overview
This project analyzes **customer shopping behavior** across **10 different shopping malls** in **Istanbul** between **2021 and 2023**.  
The goal is to uncover key insights about **customer demographics, spending habits, payment preferences, and category-wise purchase trends** to support data-driven business strategies.

The analysis was performed using:
- **SQL Server** for data preprocessing and analysis  
- **Power BI** for visualization and reporting  
- **Excel** for data verification and exports  

---

## 🎯 Objective
- To analyze customer purchase patterns across different malls.  
- To understand the relationship between **gender, age, product category, and payment methods**.  
- To identify **which segments generate more revenue** and **what products drive sales**.  
- To create a visual dashboard that helps management **make marketing and sales decisions** effectively.

---

## 🧮 Dataset Description
The dataset contains shopping details from **10 shopping malls in Istanbul**, including customer demographics and purchase data.

| **Column Name** | **Description** |
|:--|:--|
| `Invoice_No` | Unique identifier for each transaction |
| `Customer_ID` | Unique ID for each customer |
| `Gender` | Customer gender (Male / Female) |
| `Age` | Customer age |
| `Category` | Product category (e.g., Clothing, Electronics, Books, etc.) |
| `Quantity` | Number of products purchased |
| `Price` | Unit price of the product |
| `Payment_Method` | Method of payment (Cash, Credit, Debit) |
| `Invoice_Date` | Date of transaction |
| `Shopping_Mall` | Name of the shopping mall |

**Data Source:** Provided by Datamites (Internship Project)  
**Data Period:** 2021–2023  
**Tools Used:** SQL Server, Power BI, Excel  

---

## ⚙️ Methodology

### 🔹 Step 1: Data Preprocessing (SQL Server)
- Loaded raw dataset into **SQL Server**.
- Performed **data profiling** to identify duplicates, missing values, and data inconsistencies.
- Checked for **unique values** in `invoice_no` and `customer_id`.
- Cleaned and validated categorical columns such as `Gender`, `Category`, and `Payment_Method`.
- Exported the cleaned dataset into CSV format for visualization.

### 🔹 Step 2: Exploratory Data Analysis (SQL)
Executed SQL queries to answer key business questions:
- How is shopping distributed across **gender** and **age**?
- Which gender and age group **buy more products** and **generate more revenue**?
- What is the **distribution of purchase categories**?
- Which **payment methods** are most used across demographics?

### 🔹 Step 3: Visualization (Power BI)
- Imported the cleaned dataset into **Power BI**.  
- Built interactive visuals for **gender, age group, category, and payment analysis**.
- Added filters and slicers to explore patterns across malls.

---

## 📊 Power BI Dashboard Components

| **Section** | **Visual Type** | **Description** | **Key Insight** |
|--------------|----------------|-----------------|-----------------|
| **KPI Summary** | Card Visuals | Displays total revenue, total sales, and number of transactions | Quick overview of business performance |
| **Shopping Distribution by Gender** | Donut Chart | Compares purchases by gender | Females account for a higher share of purchases |
| **Revenue by Gender** | Pie Chart | Revenue contribution by gender | Females generate ~59.7% of total revenue |
| **Sales by Category and Gender** | Clustered Column Chart | Category-wise breakdown by gender | Clothing and Cosmetics dominate across both genders |
| **Shopping Distribution by Age Group** | Bar Chart | Purchase frequency across age groups | 20–30 age group makes the most purchases |
| **Revenue by Payment Method** | Stacked Bar Chart | Compares payment types | Cash dominates, followed by Credit Cards |
| **Revenue by Mall** | Column Chart | Mall-wise performance comparison | Mall of Istanbul leads in revenue generation |
| **Revenue by Category and Age** | Heatmap | Cross-analysis of revenue by product category and age | 20–30 group contributes most revenue, especially in Clothing |

---

## 📈 Key Insights

- 👩‍🦰 **Females are the top revenue generators**, contributing **~60%** of total sales.  
- 👕 **Clothing** is the most purchased category across all demographics.  
- 💳 **Cash payments** dominate (over 65%), indicating customer preference for physical transactions.  
- 👨‍🦱 The **20–30 age group** is the most active segment — highest purchases and revenue.  
- 🏬 **Mall of Istanbul** is the highest-grossing mall among all 10 locations.  

---

## 💡 Business Recommendations

- 💰 Introduce **debit/credit card promotions** to encourage digital payments.  
- 👔 Offer **male-targeted discounts** in tech and electronics categories to balance gender contribution.  
- 📚 Increase **book and lifestyle product visibility** to engage younger customers.  
- 📢 Run **seasonal campaigns** for the 20–30 demographic — the most profitable group.  
- 🧾 Focus on high-performing malls like *Mall of Istanbul* and replicate their success in others.

---

## 🧰 Tools & Technologies Used
- **SQL Server** – Data cleaning, transformation, and segmentation  
- **Power BI** – Data visualization and dashboard creation  
- **Excel** – Data verification and summary statistics  
- **Microsoft Power Query** – ETL process before visualization  

---

## 🗂️ Project Files
| File | Description |
|:--|:--|
| `SQL CUSTOMER SEGEMENT PROJECT.docx` | SQL scripts and analytical insights |
| `project customer segmentation.pbix` | Power BI interactive dashboard |
| `Customer Data Analysis ppt.pptx` | Project presentation summary |
| `README.md` | Documentation (this file) |

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-data-analysis.git
2. Open project customer segmentation.pbix in Power BI Desktop.
3. Explore the dashboard visuals interactively using filters and slicers.
4. Refer to SQL CUSTOMER SEGEMENT PROJECT.docx for SQL logic and queries.
5. Review the PowerPoint presentation for summarized findings.

🏁 **Conclusion**

The Customer Shopping Data Analysis Dashboard provides a holistic view of customer behavior across Istanbul’s top malls.
The insights reveal gender-based buying patterns, age-based trends, and payment preferences, empowering management to tailor marketing strategies and enhance revenue generation.
