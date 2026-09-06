# 🚲 Excel Bike Sales Dashboard & Analysis

An interactive Excel dashboard built to analyze customer purchasing behavior, demographics, and regional trends for a bicycle retail business. This project covers the full end-to-end data analysis workflow: from raw data cleaning and conditional transformations to dynamic pivot tables, pivot charts, and synchronized slicers.

---

## 📊 Project Overview

Understanding customer demographics is critical for targeted marketing and inventory planning in retail. This project analyzes customer attributes—such as income, marital status, age, commute distance, and region—to determine what drives bike purchases.

### **Dataset Features**
* **Demographics:** Age, Gender, Marital Status, Education, Occupation.
* **Financials & Lifestyle:** Annual Income, Number of Children, Home Ownership, Number of Cars Owned, Commute Distance, Region.
* **Target Variable:** Bike Purchase Status (`Yes` / `No`).

---

## 🛠️ Project Workflow & Methodology

The project follows a structured data analysis pipeline implemented entirely in Microsoft Excel:

### 1. Data Cleaning & Preparation (`Working Sheet`)
* **Duplicate Removal:** Cleaned the raw dataset (`bike_buyers`) by removing duplicate rows (`Data > Remove Districts/Duplicates`).
* **Value Mapping:** Standardized abbreviations using Find & Replace (`Ctrl + H`):
  * **Marital Status:** `M` $\rightarrow$ `Married`, `S` $\rightarrow$ `Single`
  * **Gender:** `M` $\rightarrow$ `Male`, `F` $\rightarrow$ `Female`
* **Age Group Categorization:** Created a custom conditional formula to segment customers into distinct age brackets:
  ```excel
  =IF(L2>54, "Old", IF(L2>=31, "Middle Age", IF(L2<31, "Adolescent", "Invalid")))
