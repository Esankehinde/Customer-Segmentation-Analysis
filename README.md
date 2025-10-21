# 🧹 Data Quality Observations

During the initial data exploration, several data inconsistencies and missing fields were identified across the provided datasets.  
These issues were noted prior to cleaning and transformation to ensure accurate analysis and reporting.

---

### 🧾 Customer Demographic Worksheet
- 87 customers do **not have a Date of Birth (DOB)** assigned.  
- **Jephthah Bachmann** has a DOB of **1843**, which is not realistic.  
- **Laraine Medendorp**, a female, was assigned gender **“F”** instead of **“Female”**, creating inconsistency in gender labeling.  
- 401 customers have **no Job Title** but are assigned an Industry.  
- The **Default column** contains codes not suitable for analysis.  
- 87 customers have an **empty Tenure** field.

---

### 🏠 Customer Address Worksheet
- Customers with IDs **3, 10, 22, and 23** have **no address assigned**.  
- Customers with IDs **4001, 4002, and 4003** have **addresses listed** but are **missing from the Customer Demography** dataset.

---

### 🆕 New Customer Worksheet
- Columns **Q, R, S, T, and U** have **no column descriptions**.  
- Under the **DOB** field, **multiple date formats** are used (e.g., “-” and “/”), and some customers have **no DOB assigned**.  
- Some customers have an **Industry assigned** but **no Job Title**.  
- New customers **do not have unique Customer IDs** assigned.

---

### ⚙️ Data Cleaning Notes
All identified issues were flagged for cleaning and standardization before loading into Power BI.  
Corrections included:
- Unifying date formats  
- Standardizing gender labels  
- Assigning missing values where possible  
- Removing invalid or duplicate entries  

---
# 🚴‍♂️ Customer Demographic & Segmentation Analysis — KPMG Virtual Internship

This project was completed as part of the **KPMG Data Analytics Virtual Internship**, focused on customer segmentation and sales performance insights for **Sprocket Central Pty Ltd**, a fictional bike retail company.  

The objective was to help the business understand **customer behavior and purchasing trends** across various demographic and socioeconomic segments, with the ultimate goal of enhancing marketing efficiency and sales targeting.

---

## 🧰 Tools & Technologies Used
| Tool | Application |
|------|--------------|
| **Microsoft Excel** | Data cleaning, transformation, and descriptive analytics (age distribution, purchase frequencies, and wealth segmentation) |
| **Power BI** | Advanced visualization and interactive dashboard development for trend and demographic insights |
| **Microsoft PowerPoint** | Executive presentation summarizing findings, trends, and strategic recommendations |

---

## 🧠 Analytical Scope
1. **Age Distribution Analysis**  
   - Determined key age brackets (41–50 years) representing the highest customer concentration.  
   - Highlighted gradual growth among customers aged 59+.

2. **Bike Purchases Over 3 Years**  
   - Quantified and compared total purchases across new and existing customers.  
   - Revealed **female customers contributed 51.6%** of total purchases, suggesting a strong emerging segment for targeted marketing.

3. **Job Industry Category**  
   - Identified **manufacturing and financial services** as dominant industries driving customer engagement.  
   - Recommended resource allocation for industry-specific marketing.

4. **Wealth Segmentation**  
   - Found **Mass Market and Affluent segments** as top-performing groups.  
   - Provided insight into aligning promotional strategies with financial capacity tiers.

5. **Car Ownership by State**  
   - Discovered **NSW, VIC, and QLD** as high car-ownership states — indicating strong disposable income and cross-selling opportunities for premium products.

---

## 📸 Visual Preview

<p align="center">
  <img src="https://github.com/Esankehinde/Customer-Segmentation-Analysis/blob/main/assets/Preview.png" alt="Power BI Dashboard Preview" width="800"/>
</p>

> _Interactive Power BI dashboard summarizing customer segmentation, wealth tiers, and purchase distribution trends._

---

## 📈 Key Learnings
- Enhanced ability to **transform raw customer data** into actionable insights using **Excel and Power BI**.  
- Strengthened understanding of **data segmentation, DAX calculations, and visualization design**.  
- Improved skill in developing **data-driven business recommendations** aligned with marketing and sales strategies.  
- Experience applying a structured analytics framework: **Data Exploration → Model Development → Insight Interpretation**.

---

## 🏢 Industrial & Organizational Applications
- **Retail & QSR:** Customer segmentation to refine loyalty programs and targeted marketing.  
- **Financial Services:** Wealth-tier analysis for personalized product offerings.  
- **Logistics & E-commerce:** Regional trend mapping to optimize route planning and distribution focus.  
- **Corporate Decision-Making:** Dashboard-driven insight reporting for performance tracking and growth strategies.

---

_“Data cleaning is where insights begin — accurate analysis starts with quality data.”_
