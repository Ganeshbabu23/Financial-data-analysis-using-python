# Financial-data-analysis-using-python
This project analyzes a financial loan dataset to reveal trends in issuance, repayments, and default risks. It cleans and segments data into “Good” and “Bad” loans, and visualizes key metrics like funded amount, repayments, and loan purposes to support better lending decisions.
# Finance Loan Data Analysis

## 📌 Project Overview
This project analyzes a financial loan dataset to identify key trends, borrower behaviors, and loan performance metrics. It involves data cleaning, exploratory data analysis (EDA), and visualization using Python libraries.

The goal is to gain actionable insights into loan disbursement patterns, repayment performance, and borrower characteristics, which can help financial institutions make better lending decisions.

---

## 📂 Dataset
- **Source**: `financial_loan.xlsx` (local dataset)
- **Content**: Contains loan applications and repayment details.
- **Key Columns**:
  - `loan_id`: Unique identifier for each loan
  - `loan_amount`: Amount funded
  - `total_payment`: Amount repaid
  - `loan_status`: Loan status (`Fully Paid`, `Current`, `Charged Off`)
  - `issue_date`, `term`, `purpose`, and other borrower details

---

## 🛠 Tools & Libraries
- **Python**
- **Pandas** – Data manipulation & analysis  
- **NumPy** – Numerical operations  
- **Matplotlib / Seaborn** – Static data visualizations  
- **Plotly Express** – Interactive visualizations  
- **Warnings** – Suppressing warning messages

---

## 🔍 Key Analysis Performed
1. **Data Cleaning**
   - Handled missing values
   - Standardized column formats
   - Removed unnecessary columns

2. **Exploratory Data Analysis**
   - Loan status distribution
   - Monthly loan trends
   - Borrower purpose analysis
   - Loan amounts vs. repayments

3. **Segmentation**
   - Good Loans (`Fully Paid`, `Current`)
   - Bad Loans (`Charged Off`)

4. **KPIs & Metrics**
   - Total funded amount
   - Total received amount
   - Average loan amount
   - Percentage of good vs. bad loans

---

## 📊 Sample Insights
- Majority of loans fall under the **Fully Paid** category.
- **Charged Off** loans form a small percentage but represent significant losses.
- The most common loan purposes are **Debt Consolidation** and **Credit Card Payments**.
- Loan issuances tend to peak during certain months of the year.

---

## 🚀 How to Run the Project
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/finance-loan-analysis.git
   cd finance-loan-analysis
