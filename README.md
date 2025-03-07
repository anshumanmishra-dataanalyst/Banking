# **Unlocking Financial Insights in Banking Data with Power BI**

## **Overview**

This repository contains the Power BI banking dashboard project developed by FinInsight Group. The dashboard is designed to deliver deep insights into banking transactions, customer account behaviors, risk assessment, and branch performance metrics. Leveraging advanced data modeling, robust DAX calculations, and interactive visualizations, this project empowers financial institutions to optimize operations, enhance customer relationships, and manage financial risks effectively.

---

## **Objective**

The primary goal of this project is to create a comprehensive and interactive Power BI dashboard that:

- Integrates transactional data with customer account details.
- Analyzes patterns in transaction behaviors and account balances.
- Assesses risk by exploring relationships among interest rates, credit scores, and loan amounts.
- Supports data-driven decision-making for improved banking services and risk management.

---

## **Key Features**

1. **Data Cleaning and Modeling**:
   - Addressed missing data, removed duplicate records, and standardized formats.
   - Merged two datasets using `AccountNumber` as the key.
   - Developed calculated columns and measures using DAX to enhance analytical capabilities.

2. **Advanced Analysis**:
   - Categorized transactions into broader groups (e.g., Inbound vs. Outbound).
   - Analyzed branch performance based on transaction volume and value.
   - Explored correlations between account balances, interest rates, and credit scores.
   - Built a risk assessment model integrating loan amounts, balances, and credit scores.

3. **Interactive Dashboard**:
   - Visualized key metrics including total transaction volume, average account balances, and branch activity.
   - Included interactive filters for account types, branches, and currencies.
   - Implemented time-based trend analyses to track account growth and transaction dynamics.

4. **Data Storytelling**:
   - Highlighted significant insights such as high-value transactions and long-standing customer profiles.
   - Provided detailed narratives and annotations within the dashboard to support strategic decision-making.

---

## **Datasets**

### **BankingDataset1.xlsx**

- Contains detailed transaction data including types, amounts, dates, and branch information.
- **Key Columns**: `TransactionID`, `AccountNumber`, `TransactionType`, `Amount`, `TransactionDate`, `BranchCode`, `Currency`, `TransactionTime`.

### **BankingDataset2.xlsx**

- Provides customer account details such as balances, interest rates, credit scores, and loan amounts.
- **Key Columns**: `AccountNumber`, `AccountHolder`, `AccountType`, `Balance`, `InterestRate`, `CreditScore`, `OpeningDate`, `LoanAmount`, `AccountHolderDetails`.

---

## **Dashboard Highlights**

### **Key Metrics**:

- Total transaction volumes and monetary values across branches.
- Average account balances segmented by account type.
- Distribution and analysis of credit scores and loan amounts.

### **Advanced Insights**:

- Correlation between interest rates and account balances.
- Identification of high-value transactions and branch activity trends.
- Predictive modeling for future account growth and risk assessment.

### **Interactive Visualizations**:

- Dynamic filters for account types, branches, and currencies.
- Time series charts for tracking transaction trends over time.
- Drill-down capabilities for detailed customer demographic and behavioral analysis.

---

## **Technologies Used**

- **Power BI**: Data modeling, DAX calculations, and interactive visualizations.
- **DAX**: Advanced measures, calculated columns, and risk assessment modeling.
- **Power Query**: Data cleaning and transformation processes.

---

## **Future Enhancements**

1. **Real-Time Data Integration**  
   - Integrate real-time transaction feeds to ensure up-to-date analytics.

2. **Expanded Data Sources**  
   - Incorporate additional datasets (e.g., online banking logs, customer feedback) for a more comprehensive analysis.

3. **Enhanced Predictive Modeling**  
   - Improve risk and growth prediction models by integrating machine learning techniques.

4. **Automated Data Refresh**  
   - Implement scheduled data refreshes through Power BI Service to maintain current insights.

---
