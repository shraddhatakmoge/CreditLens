# CreditLens – Credit Risk Analytics Platform

CreditLens is a data analytics project focused on identifying key drivers of loan default risk using Python, SQL, and Power BI.  
The project analyzes borrower behavior across credit score, debt-to-income ratio, loan purpose, income band, and interest rates to uncover high-risk lending segments.

---

## Project Overview
Financial institutions need to minimize credit losses by identifying risky borrowers early.

This project analyzes **255K+ loan records** to:
- Detect patterns behind loan defaults
- Identify high-risk borrower segments
- Build interactive dashboards for decision-making
- Provide actionable business insights for credit risk management

---


## Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL** (Data extraction & querying)
- **Power BI** (Dashboard & visualization)
- **Jupyter Notebook**

---

## Dataset Features
Main features used:
- Credit Score
- Loan Amount
- Interest Rate
- Annual Income
- Debt-to-Income Ratio (DTI)
- Employment Type
- Age Group
- Loan Purpose
- Loan Term
- Default Label

---

## Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Risk Segmentation  
4. KPI Calculation  
5. Dashboard Development  
6. Business Insight Generation  

---

## Dashboard Pages

### 1. Executive Summary
Key KPIs:
- Total Loans: **255,347**
- Total Loan Amount: **$32.58B**
- Default Rate: **11.6%**
- Avg Credit Score: **574**
- Avg Interest Rate: **13.49%**

Key Insights:
- Portfolio is skewed toward high-risk borrowers
- Low credit scores strongly correlate with default
- High DTI increases default probability

<img width="663" height="367" alt="Screenshot 2026-06-15 184140" src="https://github.com/user-attachments/assets/baaf1153-0b89-403a-bbfb-2678bf3a89d8" />


---

### 2. Loan Risk Analysis
Insights:
- Borrowers with **credit score <580** show highest default risk
- Default rises significantly when **DTI > 40%**
- Interest rates above **20%** correspond to high-risk loans

<img width="756" height="434" alt="Screenshot 2026-06-15 183945" src="https://github.com/user-attachments/assets/040b6ece-a398-4434-b2c3-6caa71466415" />


---

## Key Business Insights
- Poor credit score borrowers default at **~22–23%**
- High DTI (>40%) is a strong default indicator
- Business and Auto loans carry higher risk
- Low-income borrowers are more likely to default

---

## Repository Structure
```bash
CreditLens/
│
├── data/
├── notebooks/
└── README.md
```

---

## Future Improvements
- Build ML model for default prediction
- Deploy dashboard as web app
- Add real-time risk scoring pipeline

---

## Author
**Shraddha Takmoge**  
Aspiring Data Analyst / ML Engineer
