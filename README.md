# Loan Prediction Analysis | Excel • SQL • Power BI

This project explores the key factors that influence whether a loan application is approved or rejected.  
The dataset was cleaned and engineered in Excel, analyzed using SQL, and visualized through a Power BI dashboard.

---

## 📌 Project Objectives
- Clean and prepare raw loan data for analysis  
- Create new engineered features (Total Income, Income Band, Loan Amount Band, EMI, Credit Flags)  
- Identify trends behind loan approval decisions  
- Build SQL queries to extract business insights  
- Design a Power BI dashboard for financial decision-making

---

## 🧹 1. Excel Data Cleaning & Feature Engineering
Steps Completed:
- Removed blanks in Loan Amount, Loan Term & Credit History  
- Created:
  - `Loan_Status_Flag`
  - `Total_Income`
  - `Income_Band`
  - `Loan_Amount_Band`
  - `EMI`
  - `Credit_History_Check`
- Ensured all fields were analysis-ready for SQL and Power BI

---

## 🛢 2. SQL Analysis (SQLite)

A total of **12 SQL queries** were developed, including:

- Total applications, approvals & rejections  
- Approval rate percentage  
- Approval by gender, education & marital status  
- Loan amount & income trends  
- Approval by credit history  
- EMI distribution  
- Loan amount band analysis  
- Income band vs approval patterns  

All queries are included in `loan_sql_queries.txt`.

---

## 📊 3. Power BI Dashboard

The dashboard includes:
- **4 KPI Cards**:
  - Total Applications  
  - Total Approved  
  - Approval Rate  
  - Average EMI  
- **5 Visuals**:
  - Loan Status Count  
  - Approval by Property Area  
  - Approval by Credit History  
  - EMI by Income Band  
  - Loan Amount Band Distribution  

This provides a complete financial overview of approval behaviour and risk categories.

---

## 🧠 Key Insights
- Applicants with a **credit history = 1** had significantly higher approval rates  
- Urban and Semiurban regions saw higher approval than Rural  
- EMI tended to be lower for approved loans  
- Lower income bands applied for smaller loan amounts  
- Loan statuses showed clear patterns against income and credit flags  

---

## 🛠 Tools Used
- **Excel** – Data cleaning & feature engineering  
- **SQL (SQLiteStudio)** – Business logic queries  
- **Power BI** – Dashboard design & insights  
- **GitHub** – Version control & portfolio documentation  

---

## 📁 Repository Contents
- `loan_clean.xlsx` – Cleaned dataset  
- `loan_sql_queries.txt` – All 12 SQL queries  
- `loan_dashboard.pbix` – Power BI dashboard file  
- `README.md` – Project documentation  

---

## 📬 Contact
For collaboration or inquiries:  
**Tsitsi Maxine Ndudzo**  
LinkedIn: *Add your LinkedIn link here*

