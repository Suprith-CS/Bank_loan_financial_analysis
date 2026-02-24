Bank_loan_financial_analysis
Developed an interactive Bank Loan Analysis Dashboard using Excel and SQL to track lending performance, analyze borrower risk (Good vs Bad loans), and generate data-driven insights for portfolio management.
 
📌 Project Summary
Built a structured Bank Loan Performance Dashboard using SQL aggregations on financial loan data (Financial_loan_data). The solution evaluates lending growth, repayment performance, credit risk segmentation, and portfolio distribution across multiple dimensions.
 
🎯 Business Problem
Banks must balance revenue growth from loan disbursement with repayment stability and default risk control. This dashboard provides a centralized monitoring system to evaluate whether the portfolio is growing sustainably without increasing credit exposure.
 
🛠 Technical Implementation
Core SQL Functions Used:
COUNT() → Loan volume measurement
SUM() → Funded & repayment totals
AVG() → Interest rate & DTI calculations
GROUP BY → Multi-dimensional segmentation
Conditional aggregation → Good vs Bad loan classification
MONTH(issue_date) → Time-series analysis
All KPIs are query-driven and reproducible.
 
📊 Key Metrics Built
Loan Volume Analysis:
Total Applications
MTD vs PMTD Comparison
Capital Deployment:
Total Funded Amount
MTD vs PMTD Funded Amount
Repayment Performance:
Total Amount Received
MTD vs PMTD Collections
Risk Indicators:
Average Interest Rate
Average Debt-to-Income (DTI)
 
✅ Portfolio Quality Segmentation
Loans categorized as:
Good Loans (Fully Paid, Current)
Bad Loans (Charged Off)

Metrics Built:
Good Loan %
Bad Loan %
Funded Exposure per Segment
Amount Received per Segment
 
📈 Portfolio Breakdown Analysis
Segmented across:
Month (Trend Analysis)
State (Geographic Distribution)
Loan Term
Employment Length
Loan Purpose
Home Ownership
Each segment includes:
Loan Count
Funded Amount
Amount Received
 
🔍 Dynamic Filtering
Supports grade-level filtering (e.g., Grade A). When filters are applied, all KPIs and segment tables refresh dynamically.
 
💡 Skills Demonstrated
SQL Aggregations
Financial KPI Structuring
Risk Segmentation
Portfolio Performance Analysis
Dashboard-Oriented Data Modeling
Business-Focused Analytics
 
📂 Project Files
SQL QUERY DOCUMENT.docx → Structured SQL queries
Financial Dashboard File → Visualized KPIs
README.md → Documentation
 
📌 Outcome
Transformed raw transactional loan data into a structured performance monitoring dashboard providing visibility into lending activity, capital exposure, repayment efficiency, and portfolio quality distribution.
