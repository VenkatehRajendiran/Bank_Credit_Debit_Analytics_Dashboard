# 📊 Bank Debit & Credit Analytics Dashboard

This project is an **interactive Excel-based dashboard** that analyzes customer banking transactions to uncover patterns, trends, and potential anomalies. The dashboard leverages KPIs and visualizations to offer actionable insights for both operational efficiency and risk management.

---

## 📁 Files Included

- **Bank_Debit_Credit_Analytics.xlsb** – Contains the full working Excel dashboard with formulas, slicers, and visuals.
- **dashboard.png** – A screenshot preview of the dashboard interface.

---

## 🔍 Key Performance Indicators (KPIs)

### 1. **Total Credit Amount**
- **Formula:** `SUMIFS(Amount, Transaction Type, "Credit")`
- **Purpose:** Measures the total amount deposited across all transactions.

### 2. **Total Debit Amount**
- **Formula:** `SUMIFS(Amount, Transaction Type, "Debit")`
- **Purpose:** Represents total money withdrawn or spent.

### 3. **Credit to Debit Ratio**
- **Formula:** `Total Credit Amount ÷ Total Debit Amount`
- **Purpose:** Evaluates the balance between incoming (credit) and outgoing (debit) funds.

### 4. **Net Transaction Amount**
- **Formula:** `Total Credit - Total Debit`
- **Purpose:** Indicates overall cash flow; whether the account saw a net gain or loss.

### 5. **Account Activity Ratio**
- **Formula:** `Total Number of Transactions ÷ Account Balance`
- **Purpose:** Reflects how active an account is relative to its balance.

### 6. **Transaction Volume Over Time**
- **Formula:** Count of transactions per Day / Week / Month
- **Purpose:** Detects transaction trends and seasonal behaviors.

### 7. **Transaction Value by Branch**
- **Formula:** `SUMIFS(Amount, Branch)`
- **Purpose:** Compares total transaction amounts between branches.

### 8. **Transaction Volume by Bank**
- **Formula:** `SUMIFS(Amount, Bank Name)`
- **Purpose:** Identifies performance differences across banks.

### 9. **Transaction Method Distribution**
- **Formula:** Percentage share by method (e.g., Card, UPI, Bank Transfer)
- **Purpose:** Highlights user preferences in transaction methods.

### 10. **Branch Transaction Growth**
- **Formula:** `% Change = (Current Period - Previous Period) / Previous Period`
- **Purpose:** Monitors branch-wise performance over time.

### 11. **High-Risk Transaction Flag**
- **Formula:** IF transaction > threshold OR irregular behavior → Flag
- **Purpose:** Detects outliers or potential fraud.

### 12. **Suspicious Transaction Frequency**
- **Formula:** Count of flagged transactions in a given period
- **Purpose:** Monitors recurrence of abnormal or risky behavior.

## ⚙️ Tools & Techniques Used

- **Microsoft Excel (.xlsb format)**
- Advanced Excel formulas
- Pivot Tables & Charts
- Slicers & Interactivity

## 👤 Author

**Venkateh Rajendiran**  
Data Analytics Enthusiast | Excel & BI Tools Practitioner

---

## 💬 Contact

For queries, suggestions, or collaboration opportunities, feel free to connect via:
- https://www.linkedin.com/in/venkatesh02r/
- venkatesh02r@gmail.com
- 9585252035
---

## 📌 Note

This dashboard is built as part of my Data Analyst learning journey and demonstrates real-time transaction analytics in a simplified, secure environment. No actual personal or sensitive data is used.

