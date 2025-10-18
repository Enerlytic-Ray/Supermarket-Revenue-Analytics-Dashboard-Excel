# 🧾 Revenue Analysis Dashboard- Excel Project

![Revenue Analysis Dashboard](./Revenue%20Analysis%20DashBoard%202.jpg)

---

## 📊 Project Overview

This project presents a **Revenue Analysis Dashboard** designed using **Microsoft Excel** to analyze supermarket sales data.  
It explores business performance through **interactive visualization** and **data-driven storytelling**, highlighting sales patterns, product performance, customer segmentation, and gender-based revenue trends.  

The analysis follows the **PPDAC (Problem–Plan–Data–Analysis–Conclusion)** framework, demonstrating a structured, research-oriented approach to business analytics.

---

## 🔍 PPDAC Framework

### 🧩 Problem Definition
Supermarket branches operate across multiple locations, generating large volumes of transactional data.  
The challenge is to **identify key revenue drivers** and **understand customer purchasing behaviors**- enabling data driven business decisions in areas like:
- Product line profitability  
- Payment method efficiency  
- Gender-based spending behavior  
- Branch and time-based performance  

**Key Business Question:**  
> How can the supermarket optimize product and branch performance to maximize total revenue and customer satisfaction?

---

### 🧭 Plan
To answer this, a step-by-step analytics workflow was developed:
1. **Data Source:** `supermarket_sales 2.xlsx` (raw transactional dataset)
2. **Tools Used:**  
   - Microsoft Excel (Data Cleaning, KPI Calculations, Dashboard Design)
   - Pivot Tables & Charts for Visualization
   - Conditional Formatting and Named Ranges for Dynamic Analysis
3. **Methodology:**  
   - Data cleaning and transformation  
   - Computation of business KPIs  
   - Dashboard visualization & storytelling  

---

## 📈 Data
**Dataset:** [`supermarket_sales 2.xlsx`](./supermarket_sales%202.xlsx)  
**Rows:** 1,000  
**Columns:** 17  

**Key Fields:**  
`Invoice ID`, `Branch`, `City`, `Customer Type`, `Gender`, `Product Line`,  
`Unit Price`, `Quantity`, `Tax`, `Total`, `Date`, `Payment`,  
`Gross Margin %`, `Rating`

---

## 🧮 Excel Data Cleaning & KPI Calculation Process

### 🧹 Data Cleaning Steps:
| Step | Action | Excel Technique Used |
|------|---------|----------------------|
| 1 | Removed duplicate and blank rows | `Remove Duplicates`, `Filter` |
| 2 | Checked for missing gender/product data | `COUNTBLANK()` |
| 3 | Standardized categorical entries (e.g., Payment Type) | `PROPER()` |
| 4 | Converted dates to proper Excel format | `DATEVALUE()` |
| 5 | Verified numeric columns for errors | `ISNUMBER()` checks |

---

### 💡 KPI Calculations

| KPI | Formula | Description |
|------|----------|-------------|
| **Total Revenue** | `=SUM(Total)` | Total sales across all transactions |
| **Total Quantity Sold** | `=SUM(Quantity)` | Number of items sold |
| **Average Revenue per Branch** | `=AVERAGEIFS(Total, Branch, BranchName)` | Compares performance across branches |
| **Gender-Based Revenue** | `=SUMIFS(Total, Gender, "Male")` and `=SUMIFS(Total, Gender, "Female")` | Evaluates gender contribution to sales |
| **Payment Method % Split** | `=COUNTIF(Payment, "Cash")/COUNTA(Payment)` | Shows share of each payment type |
| **Product Line Revenue** | `=SUMIFS(Total, [Product Line], "Food and Beverages")` | Identifies top-performing product lines |

---

## 📊 Dashboard Components

The final **Excel Dashboard** visualizes key business insights:

| Insight | Visualization Type | Description |
|----------|--------------------|--------------|
| **Product by Revenue** | Bar Chart | Highlights top-performing product lines |
| **% of Payment by Revenue** | Donut Chart | Compares preferred payment methods |
| **Customer Type by Revenue** | Column Chart | Analyzes spending by member vs. normal customers |
| **Gender by Revenue** | Bar Chart | Evaluates gender contribution to revenue |
| **Filters (Branch & Date)** | Slicers | Enables interactive analysis by branch and time |

📸 **Dashboard Preview:**  
![Revenue Analysis Dashboard](./Revenue%20Analysis%20DashBoard%202.jpg)

---

## 🧠 Analysis & Insights

- **Food & Beverages** and **Sports & Travel** are top contributors to total revenue.  
- **Members** generate slightly more revenue than **normal** customers — suggesting loyalty impact.  
- **Male** customers contribute a higher share of total revenue.  
- **Cash** remains the most dominant payment method (~35%).  
- **Branch A** leads in sales volume, while **Branch C** shows potential for growth.

---

## 🧩 Conclusion

The analysis shows clear patterns in **customer demographics**, **product preferences**, and **payment behaviors**.  
This structured PPDAC approach demonstrates **how simple Excel analytics can reveal business insights** — bridging the gap between raw data and informed decision-making.

---

## 🚀 Key Takeaways

- Combines **data cleaning, KPI design, and dashboard storytelling**  
- Applies **PPDAC** for clarity and analytical depth  
- Demonstrates **quantitative thinking** and **data-driven decision support**  
- Suitable for **Business Analysts**, **Data Analysts**, and **BI professionals**

---

## 💼 About the Author

**👤 Adejoro Raymond Olaotan**  
Data & Business Analyst | Excel • Tableau • Power BI • Python • SQL  
📧 [Contact on LinkedIn](#) | 🌐 [Portfolio Website (Coming Soon)](#)
