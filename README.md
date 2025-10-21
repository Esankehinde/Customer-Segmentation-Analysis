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

_“Data cleaning is where insights begin — accurate analysis starts with quality data.”_
