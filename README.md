# Bank Loan Analysis 📊

A data-driven analysis of **38,576 consumer loan applications** using **PostgreSQL** and **Power BI**, uncovering loan performance, risk exposure (good vs. bad loans), and borrower characteristics across a **$435.7M loan portfolio**.

---

## 🎯 Project Overview

This project analyzes a bank's consumer loan portfolio to give stakeholders a clear, data-driven view of:
- Overall loan performance and KPIs
- Loan risk (Good vs. Bad loans)
- Borrower characteristics that drive lending volume

SQL was used to clean the data and answer key business questions. The results were visualized in an interactive **3-page Power BI dashboard** (Summary, Overview, Details) with slicers for Purpose, Grade, and State.

---

## 📁 Repository Structure

```
bank-loan-analysis/
│
├── data/
│   └── financial_loan.csv          # Raw dataset (38,576 rows, 24 columns)
│
├── sql/
│   └── SQL_queries.pdf             # All PostgreSQL analysis queries (KPIs, trends, breakdowns)
│
├── dashboard/
│   └── bank_loan_dashboard.pdf     # Power BI dashboard screenshots (Summary/Overview/Details)
│
├── reports/
│   └── Bank_Loan_Analysis_Report.pdf  # Full written project report with insights & recommendations
│
├── presentation/
│   └── Bank-Loan-Analysis.pdf      # Slide deck summary of the project
│
└── README.md
```

---

## 🗄️ Dataset

- **Rows:** 38,576
- **Columns:** 24
- **Key fields:** borrower profile (state, employment length, home ownership, income, DTI), loan details (amount, term, interest rate, grade, purpose), loan status, and repayment outcome

---

## 🔑 Key Metrics (Overall KPIs)

| KPI | Total | MTD (Dec) | MoM Change |
|---|---|---|---|
| Loan Applications | 38,576 | 4,314 | ▲ 6.9% |
| Total Funded Amount | $435.7M | $53.9M | ▲ 13.0% |
| Total Amount Received | $473.0M | $58.0M | ▲ 15.8% |
| Avg. Interest Rate | 12.05% | 12.36% | ▲ 3.5% |
| Avg. DTI | 13.33% | 13.67% | ▲ 2.8% |

## 🟢🔴 Good vs. Bad Loans

- **Good Loans** (Fully Paid + Current): 86.18% of applications — $370.2M funded, $435.7M recovered
- **Bad Loans** (Charged Off): 13.82% of applications — $65.5M funded, only $37.2M recovered
- **Key Insight:** The bank lost roughly **$28M** on charged-off loans

---

## 📈 Dashboard Highlights

1. **Summary Page** — Headline KPIs, Good vs. Bad Loan breakdown, Loan Status grid
2. **Overview Page** — Trends by month, state, term, employment length, purpose, and home ownership
3. **Details Page** — Row-level grid of individual loan records

---

## 💡 Business Recommendations

- **Reduce bad-loan exposure** — Tighten underwriting (DTI thresholds, grade-based limits) for risky segments
- **Reward stable borrowers** — Preferential rates for borrowers with 10+ years of employment
- **Double down on top purposes** — Debt consolidation and credit card refinancing dominate demand
- **Focus regional efforts** — CA, NY, TX, and FL drive the bulk of loan volume
- **Plan for continued growth** — Loan volume nearly doubled year-over-year
- **Watch active loans** — Current loans carry the highest average interest rate (15.10%)

---

## 🛠️ Tools Used

- **PostgreSQL** — data cleaning and SQL analysis (KPIs, trends, segmentation)
- **Power BI** — interactive 3-page dashboard with dynamic slicers
- **DAX** — calculated measures for KPIs and MoM comparisons

---

Built by Sneha Shingade(https://github.com/Snehashingade)
