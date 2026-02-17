# Telecom Customer Churn Analysis

A business analytics project that investigates why telecom customers leave (churn) and proposes retention strategies using Python for data preparation and Power BI for interactive dashboards.

---

## Overview

Customer churn significantly impacts telecom revenue because acquiring a new customer costs more than retaining an existing one. This project analyzes behavioral, service, and billing attributes to identify high‑risk customer segments and actionable levers to reduce attrition.

**Author:** Ayush Rawat
**Institution:** Graphic Era Hill University
**Tools:** Python (Pandas, NumPy, Seaborn), Power BI

---

## Objectives

* Calculate overall churn rate and customer distribution
* Identify churn drivers (contract, tenure, pricing, services, payment)
* Segment customers by risk
* Provide data‑driven retention recommendations

---

## Dataset

Public telecom dataset containing **7,043 customers** with demographics, subscription details, billing information, and churn status.

Key fields:

* `tenure` – months with company
* `MonthlyCharges` – monthly fee
* `TotalCharges` – total billed
* `Contract` – month-to-month / yearly / two-year
* `InternetService` – DSL / Fiber / None
* `PaymentMethod` – payment mode
* `TechSupport`, `OnlineSecurity` – service add-ons
* `Churn` – Yes/No (target variable)

---

## Project Workflow

1. **Data Cleaning (Python)**

   * Convert `TotalCharges` to numeric
   * Handle missing values
   * Remove invalid records
   * Create `TenureGroup` cohorts

2. **Exploratory Analysis**

   * Churn distribution
   * Contract analysis
   * Tenure lifecycle behavior
   * Service and payment impact

3. **Dashboarding (Power BI)**

   * Executive KPIs
   * Risk segmentation visuals
   * Interactive filters and drilldowns

---

## Key Findings

* Overall churn rate ≈ **27%**
* Month‑to‑month contracts show the highest churn
* First‑year customers are most vulnerable
* Higher monthly charges increase churn probability
* Customers without technical support churn significantly more
* Electronic check users show elevated churn

---

## Business Recommendations

* Encourage long‑term contracts with discounts
* Improve onboarding in the first 90 days
* Bundle security and technical support services
* Incentivize automatic payments
* Review pricing of high‑cost plans

---

## Dashboard

> Add screenshots of your Power BI pages below

### Executive Overview

<img width="1210" height="751" alt="image" src="https://github.com/user-attachments/assets/d484e2c8-2d4d-42b4-861c-a8a350535e03" />


### Churn Risk Analysis

<img width="1212" height="750" alt="image" src="https://github.com/user-attachments/assets/547ce8d6-0373-412a-8b87-06dd952c88fd" />


---


## How to Run (Python Analysis)

```bash
pip install pandas numpy seaborn matplotlib
jupyter notebook
```

Open `Telecom_customer_churn_dashboard.ipynb` and run all cells.

---

## Dashboard Usage

1. Open `churn_dashboard.pbix` in Power BI Desktop
2. Use slicers to filter by gender, contract, or tenure group
3. Review risk segments and KPI cards

---

## Future Improvements

* Build churn prediction model (Logistic Regression / Random Forest)
* Deploy dashboard to Power BI Service
* Add customer lifetime value analysis

---

## Contact

**Ayush Rawat**
Email: rawatayush608@gmail.com
LinkedIn: www.linkedin.com/in/ayush-rawat-817404252

---

*This project demonstrates end‑to‑end data analytics workflow: data cleaning → analysis → visualization → business recommendation.*
