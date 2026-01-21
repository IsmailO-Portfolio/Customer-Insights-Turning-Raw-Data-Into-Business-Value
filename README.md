# Customer Insights: Analysing Banking Trends accross Nigeria

A data cleaning and customer insights project focused on analyzing banking customer trends across Nigeria using **Power Query**. The dataset was intentionally designed with inconsistencies and errors to simulate real world dirty data and demonstrate structured data transformation, validation, and insight generation.

---

## 🧾 Project Overview

Wilogistics, an independent customer insights research company, conducted this analysis to understand customer behavior within Nigeria’s banking and fintech ecosystem.

The project involved:
- Cleaning and standardizing raw customer data
- Preparing the dataset for analysis
- Extracting meaningful demographic and financial insights

The final output is an analysis-ready dataset suitable for business intelligence, reporting, and decision making.

## [Dataset 1](https://github.com/IsmailO-Portfolio/Customer-Insights-Turning-Raw-Data-Into-Business-Value/blob/main/dirty_nigerian_customer_data.xlsx)
## [Dataset 2](https://github.com/IsmailO-Portfolio/Customer-Insights-Turning-Raw-Data-Into-Business-Value/blob/main/nigerian_dirty_customer_data.xlsx)


---

## 📂 Dataset Description

The cleaned dataset contains over **1,000 customer records** spanning all **36 Nigerian states**.

### Included Attributes
- 👤 Customer Name  
- ⚧ Gender  
- 💼 Occupation  
- 💰 Annual Income  
- 🎂 Date of Birth  
- 📅 Derived Year (from Date of Birth)  
- 🏦 Bank / FinTech Provider  
- 📝 Purpose of Account Opening  
- 📍 State of Residence  

The derived **Year** column enables age based segmentation and trend analysis.

---

## ⚙️ Data Transformation Process (Power Query)

All transformations were carried out using **Microsoft Power Query**.

### Step by Step Applied Steps

1. **🔌 Data Source Connection**  
   Imported the raw dataset into Power Query, preserving original records before transformation.

2. **🔢 Changed Data Types**  
   - Date of Birth converted to `Date`
   - Annual Income converted from `Text` to numeric format  
   Invalid values were handled later.

3. **✏️ Renamed Columns**  
   Standardized column names for clarity and consistency.

4. **🔠 Capitalized Text**  
   Applied *Capitalize Each Word* to text columns such as:
   - Customer Name  
   - Gender  
   - Occupation  

5. **✂️ Trimmed Text**  
   Removed leading, trailing, and excess spaces from all text fields.

6. **🧹 Cleaned Text**  
   Removed non printable and hidden characters to prevent filtering and comparison issues.

7. **🔁 Replaced Values**  
   Standardized inconsistent entries in columns like Gender and Occupation.

8. **❌ Removed Errors**  
   Rows with conversion errors (especially in Date of Birth and Annual Income) were removed.

9. **📆 Inserted Year Column**  
   Extracted the year from Date of Birth to support age segmentation.

10. **🗑️ Removed Blank Rows**  
    Eliminated empty or near empty records to improve data quality.

## ![Cleaning Steps](https://github.com/IsmailO-Portfolio/Customer-Insights-Turning-Raw-Data-Into-Business-Value/blob/main/Steps%20in%20Power%20Query.jpeg)

---

## 📈 Key Insights & Findings

### ⚧ Gender Distribution
- Female customers significantly outnumber male customers.
- Indicates stronger engagement from women.
- Opportunity for women focused financial products.

---

### 🎯 Age Distribution
- Birth years range from the 1940s to 2009.
- Customer groups include:
  - Teenagers (16–19)
  - Young adults (20–35)
  - Middle aged adults (36–55)
  - Elderly (56+)
- Supports age specific banking products.

---

### 💼 Occupation Analysis

High representation from a few occupation groups, especially the informal sector.

| Occupation     | Count | Percentage |
|----------------|-------|------------|
| Engineer       | 74    | 10.9%      |
| Unemployed     | 71    | 10.5%      |
| Tailor         | 69    | 10.2%      |
| Trader         | 66    | 9.7%       |
| Teacher        | 63    | 9.3%       |
| Nurse          | 62    | 9.1%       |
| Developer      | 62    | 9.1%       |

This highlights strong demand for:
- SME products
- Microfinance solutions
- Informal sector banking services

---

### 📍 Geographic Coverage
- Customers are represented across **all 36 Nigerian states**.
- Higher concentrations observed in:
  - Bauchi
  - Nasarawa
  - Yobe
  - Ebonyi
  - Borno
  - Kogi  

These states present strong customer acquisition opportunities.

---

### 🏦 Bank & FinTech Usage
- Strong adoption of FinTech platforms such as:
  - Opay
  - Kuda
  - Palmpay
  - Moniepoint
- Traditional banks dominate salary accounts, fixed deposits, and dollar cards.
- FinTechs lead in fast, low fee, mobile first banking.

## [Overall Dataset (Cleaned)](https://github.com/IsmailO-Portfolio/Customer-Insights-Turning-Raw-Data-Into-Business-Value/blob/main/Cleaned%20with%20Power%20Query.xlsx)

---

## 🧠 Summary

- 🚀 FinTech adoption is high across Nigeria  
- 👩 Female customers dominate the dataset  
- 🛠️ Traders and artisans form a major customer segment  
- 🗺️ Nationwide customer representation  
- 📊 Dataset is fully cleaned and analysis ready  




---

## 🛠️ Tools Used
- Microsoft Power Query  
- Microsoft Excel  

---

## 📌 Use Cases
- Customer segmentation  
- Banking product strategy  
- Financial behavior analysis  
- Business intelligence reporting  

---

**Author:** Zen  
