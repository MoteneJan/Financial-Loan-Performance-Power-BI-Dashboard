# FinTech Bank Loan Analysis Dashboard | Power BI

![Dashboard Header](screenshots/overview-page.png)

Modern interactive Power BI dashboard designed to monitor and analyze a bank's / fintech lending portfolio.  
Inspired by real-world consumer loan data (similar to LendingClub format).

## 🎯 Key Business Insights Available

- **Overall KPIs**  
  - Total Loan Applications: **38.6K**  
  - Total Funded Amount: **$435.7M**  
  - Total Amount Received: **$473.0M**  
  - Average Interest Rate: ~12%  
  - Average DTI (Debt-to-Income): ~13.3%

- **Performance Split**  
  - Good Loans: **86.2%** ($370M funded)  
  - Bad Loans: **13.8%** ($65.5M funded)

- **Trends & Distributions**  
  - Funded amount growth by month  
  - Applications & funding by U.S. state  
  - Loan purpose breakdown (Debt Consolidation, Credit Card, Home Improvement, etc.)  
  - Term distribution (36 vs 60 months)  
  - Grade & sub-grade performance  
  - Home ownership impact (Rent vs Mortgage vs Own)

- **Detailed View**  
  - Granular table with: ID, Purpose, Home Ownership, Grade, Issue Date, Amount, Interest Rate, Installment, Total Received

## 📊 Dashboard Pages

1. **Summary** – High-level KPIs, good vs bad loans gauges, loan status table  
2. **Overview** – Trend charts, geographic map, purpose bar, KPI cards with MoM change  
3. **Details** – Transaction-level table (drillable)

## 🛠️ Tech Stack

- **Power BI Desktop** (DAX + Power Query)
- **Data Source**: Financial loan dataset (~38–39K records)
- **Visuals**: Cards, Line charts, Map, Donut/Gauge, Bar/Column, Table/matrix

## 📸 Screenshots

### Overview Page
![Overview](screenshots/overview-page.png)

### Summary / Good vs Bad View (from tutorial reference)
![Summary](screenshots/summary-page-from-video.png)

## 📂 How to Use This Project

1. Clone the repository  
   ```bash
   git clone https://github.com/Emjay-Moh/FinTech-Bank-Loan-Analysis-PowerBI.git
