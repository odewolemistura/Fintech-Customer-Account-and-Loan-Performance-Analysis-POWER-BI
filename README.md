# Fintech Customer & Loan Analysis Dashboard (Power BI)

## Project Overview

This project explores customer profiles, account activities, and loan performance using Power BI. The aim is to provide business insights into customer behavior and credit performance to support better product offerings, risk management, and marketing strategies.

The analysis is split into two pages:
1. **Customer & Account Insights**
2. **Loan & Credit Performance**

## 📁 Data Source

The dataset was obtained from **Kaggle**. It contains synthetic records on:
- Customer demographics and financial behavior  
- Account activities (balance, deposits, withdrawals, transfers)  
- Loan application summaries (loan amounts, status, interest, purpose)  
- Investment goals and risk tolerance  

## 🛠 Tools Used

- **Power BI** – For visualization and dashboard creation  
- **Power Query (inside Power BI)** – For data cleaning and transformation  

## Data Cleaning and Preparation

Performed in **Power Query**, the cleaning process involved:
- Removing irrelevant columns  
- Standardizing and formatting text and numeric values  
- Ensuring correct data types  
- Renaming columns for clarity  
- Rearranging columns logically  
- Grouping:
  - **Age ranges** (e.g., 18–29, 30–44, 45-64, 65+ etc.)
  - **Income levels** (Low, Medium, High)
## 🔍 Exploratory Data Analysis

### 📄 Page 1: Customer & Account Insights
- Examined customer demographics and financial engagement  
- Identified transaction behavior by account type  
- Investigated customer distribution across regions and income brackets  

### 📄 Page 2: Loan & Credit Performance
- Explored loan approval rates by customer attributes  
- Evaluated loan purpose trends  
- Analyzed loan amounts and interest rates across regions and income levels  

## 📊 Data Analysis (Key Findings)

### Page 1 – Customer & Account Insights
- **Total customers**
- **Average deposit**  
- **Average withdrawal** 
- **Region**: Australia has the highest number of customers (182); North America has the least (149)  
- **Account Type**:
  - Savings: 25.6%  
  - Credit: 25.4%  
  - Checking: 25.1%  
  - Investment: 23.9%  
- **Withdrawals**: Highest in **Credit accounts**, lowest in **Savings**  
- **Deposits**: Highest in **Credit accounts**, lowest in **Savings**  
- **Income**: **91% of customers** earn less than **$40K**  
- **Investment goals by risk tolerance**:
  - High-risk: Speculation  
  - Low-risk: Growth  
  - Medium-risk: Mostly speculation  
- **Highest accessible balance**: $1,009  

### Page 2 – Loan & Credit Performance
- **Loan Approval Status**:
  - Approved: 48%  
  - Pending: 28%  
  - Rejected: 26%  
- **Loan status by financial history**:
  - Good history → More approvals  
  - Poor history → More rejections  
- **Loan purposes**:
  - Most common: **Medical expenses**  
  - Least common: **Small business**  
- **Loan status by employment**:
  - Employed & Retired: Mostly **Pending**  
  - Self-employed: Highest **Approved**  
- **Average loan amount**:
  - Highest in **Australia**  
  - Lowest in **Africa**  
- **Average interest rate by income**:
  - High income: 0.12  
  - Medium income: 0.11  
  - Low income: 0.08  
- Loan amounts followed the same trend as interest rates  

## ✅ Findings & Results Summary

- Most users are low-income earners under $40K, yet credit accounts see the highest deposit and withdrawal activity.  
- Customers with high-risk tolerance are more likely to invest in speculation.  
- Loan approval is strongly linked to **financial history** and **employment type**.  
- Regional disparities exist in loan amounts, with **Australia** leading in both loan size and customer base.  

## 💡 Recommendations

- **Target high-performing regions** (e.g., Australia) for premium services and upselling.  
- **Encourage savings** among low-income users by offering incentives or personalized goals.  
- **Improve credit evaluation models** by giving more weight to employment type and financial history.  
- **Develop tailored loan packages** for self-employed users, who have higher approval rates.  

## ⚠️ Limitations

- Data is synthetic and may not represent real-world customer behavior.  
- Time-based trends and seasonality were not analyzed.  
- The dataset lacks credit score data, which is a key variable in financial lending.  
