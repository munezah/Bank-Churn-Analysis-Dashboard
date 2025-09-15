# Bank Customer Churn Dashboard – Excel Project  

An interactive, insight-driven Excel dashboard analyzing customer churn for a retail bank. This project transforms raw customer data into a dynamic business intelligence tool using Microsoft Excel and SQL Developer, enabling decision-makers and stakeholders to track churn patterns, satisfaction trends, customer demographics, and loyalty drivers.  

---

## Dataset  

The dataset used in this project includes details such as:  
- **Customer demographics** (Age, Gender, Geography)  
- **Account information** (Balance, Tenure, Card Type, Products)  
- **Behavioral factors** (Complaints, Satisfaction Score, Active Member status)  
- **Derived fields** created in **SQL Developer** for deeper insights:  
  - `AgeGroup`  
  - `BalanceCategory`  
  - `TenureLevel`  
  - `SatisfactionScoreLevel`  
  - `IsHighValueCustomer`  

**[Download Dataset From Source (Excel File)](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn/data)**

---

## Key Performance Indicators (KPIs) Tracked  

This dashboard helps answer critical business questions such as:  

- **Churn Rate**  
  What percentage of customers have exited the bank.  

- **Churn by Gender & Age Group**  
  Which demographics are more likely to churn.  

- **Churn by Geography**  
  How customer attrition varies across different regions.  

- **Customer Satisfaction Analysis**  
  Average satisfaction scores by tenure and complaint status.  

- **Complaints vs Churn**  
  How customer complaints impact churn likelihood.  

- **High Value Customers**  
  Identifying and analyzing churn within profitable customer segments.  

---

### 1. Data Preparation (SQL Developer)  
- Wrote **SQL queries** to add new columns and segment customers:  
  - `AgeGroup` → Created age brackets (18–25, 26–35, etc.)  
  - `BalanceCategory` → Classified customers as Zero, Low, Medium, High balance  
  - `TenureLevel` → Grouped customers into New, Loyal, Long-Term  
  - `SatisfactionScoreLevel` → Translated numeric scores into Low/Medium/High  
  - `IsHighValueCustomer` → Flagged based on balance, products, and tenure  
- Cleaned and validated raw data before exporting to Excel.  

### 2. Data Cleaning (Excel)  
- Standardized categorical fields (Gender, Geography, Card Type).    
- Imported SQL-enhanced dataset for dashboard creation.  

### 3. Data Visualization (Excel)  
- **Donut Charts:** Churn by Gender, Tenure Level  
- **Bar Charts:** Churn by Location, Complaints, Age Groups  
- **Line Chart:** Customer Churn by Age  
- **KPI Cards:** Churn Rate, Average Age, Satisfaction, Tenure  
- **Slicers & Filters:** Interactive exploration by Geography, Gender, AgeGroup, Satisfaction   

---

## Process of Building This Dashboard  

1. **Imported & Reviewed Data**  
   Explored dataset for key attributes related to churn.  

2. **Data Cleaning & Preparation**  
   Fixed inconsistencies and created derived fields for segmentation.  

3. **Data Modeling**  
   Defined churn, satisfaction levels, and high-value customers for analysis.  

4. **Built PivotTables**  
   Aggregated churn metrics across multiple dimensions (gender, geography, age group, tenure).  

5. **Designed the Dashboard**  
   Created charts, and slicers. Finalized layout for clarity and interactivity.  

---

## Dashboard View  

![Dashboard](https://github.com/munezah/Bank-Churn-Analysis-Dashboard/blob/main/bank%20dashboard%20Image.png)  

---

## Files Included  

- `BbankDashboard.xlsx` – Final interactive dashboard  
- `Customer-Churn-Records dataset.csv` – Raw + derived dataset  
- `bank dashboard Image.png` – Final dashboard image  
- `README.md` – Project documentation (this file)  

---

## Contact  

For feedback, collaboration, or questions:  

**Munezah Waqar**  
📧 munezahwaqar@gmail.com  

🔗 [LinkedIn Profile](https://www.linkedin.com/in/munezah-waqar/)  

📞 +92-331-3317586  

🌐 [Portfolio Website](https://munezahwaqar.info)  
