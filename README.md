# Bank Loan Financial Analysis Dashboard

Developed an interactive **Bank Loan Analysis Dashboard** using Excel and SQL to track lending performance, analyze borrower risk (Good vs. Bad loans), and generate data-driven insights for portfolio management.

## 📌 Project Summary
Built a structured Bank Loan Performance Dashboard using SQL aggregations on financial loan data. The solution evaluates lending growth, repayment performance, credit risk segmentation, and portfolio distribution across multiple dimensions.

## 🎯 Business Problem
Banks must balance revenue growth from loan disbursement with repayment stability and default risk control. This dashboard provides a centralized monitoring system to evaluate whether the portfolio is growing sustainably without increasing credit exposure.

## 🛠 Technical Implementation
**Core SQL Functions Used:**
* `COUNT()` → Loan volume measurement
* `SUM()` → Funded & repayment totals
* `AVG()` → Interest rate & DTI calculations
* `GROUP BY` → Multi-dimensional segmentation
* `Conditional Aggregation` → Good vs. Bad loan classification
* `MONTH(issue_date)` → Time-series analysis

*All KPIs are query-driven and reproducible.*

## 📊 Key Metrics Built
### 1. Loan Volume Analysis
* Total Applications
* MTD (Month-to-Date) vs. PMTD (Previous Month-to-Date) Comparison

### 2. Capital Deployment
* Total Funded Amount
* MTD vs. PMTD Funded Amount

### 3. Repayment Performance
* Total Amount Received
* MTD vs. PMTD Collections

### 4. Risk Indicators
* Average Interest Rate
* Average Debt-to-Income (DTI)

## ✅ Portfolio Quality Segmentation
Loans are categorized as:
* **Good Loans:** Fully Paid, Current
* **Bad Loans:** Charged Off

**Metrics Built per Segment:**
* Good Loan % vs. Bad Loan %
* Funded Exposure per Segment
* Amount Received per Segment

## 📈 Portfolio Breakdown Analysis
The data is segmented across multiple dimensions for deep-dive analysis:
* **Month:** Trend Analysis
* **State:** Geographic Distribution
* **Loan Term:** (36 months vs. 60 months)
* **Employment Length:** Stability Analysis
* **Loan Purpose:** Reason for borrowing
* **Home Ownership:** Mortgage, Rent, Own

Each segment includes metrics for **Loan Count**, **Funded Amount**, and **Amount Received**.

## 🔍 Dynamic Filtering
The dashboard supports grade-level filtering (e.g., Grade A, B, C). When filters are applied, all KPIs and segment tables refresh dynamically to provide specific insights.

## 💡 Skills Demonstrated
* Advanced SQL
* Financial KPI Structuring
* Risk Segmentation & Mitigation Analysis
* Portfolio Performance Monitoring
* Dashboard-Oriented Data Modeling
* Business-Focused Analytics

## 📂 Project Files
* `SQL QUERY DOCUMENT.docx` – Structured SQL queries used for data extraction.
* `Financial Dashboard.xlsx` – The final visualized interactive dashboard.
* `README.md` – Project documentation.

## 📌 Outcome
Transformed raw transactional loan data into a structured performance monitoring dashboard, providing management with clear visibility into lending activity, capital exposure, repayment efficiency, and portfolio quality distribution.

## 📬 Contact
For queries or collaboration, feel free to connect via www.linkedin.com/in/suprithcs.
