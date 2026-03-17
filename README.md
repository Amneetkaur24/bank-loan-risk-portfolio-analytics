# Power BI Bank Loan Risk Portfolio Analytics
<img width="887" height="491" alt="Screenshot 2026-03-16 171252" src="https://github.com/user-attachments/assets/bc9ea768-86de-4b1b-997c-3330ce1c436a" />
<img width="887" height="496" alt="Screenshot 2026-03-16 171351" src="https://github.com/user-attachments/assets/fb4abc2c-3170-4504-8b8c-d19e074c410b" />

## Overview

This project analyzes bank lending performance by monitoring loan issuance, repayment behavior, and portfolio risk indicators. The dashboard provides a consolidated view of loan application metrics, funding trends, borrower characteristics, and loan quality indicators.

The objective of this dashboard is to help financial institutions track lending performance, evaluate borrower risk, and monitor portfolio health using interactive data analytics.

## Business Objective

Banks and lending institutions must continuously monitor loan portfolios to understand funding distribution, repayment trends, and default risk exposure.

This dashboard was developed to support:

• Monitoring of loan issuance and repayment performance
• Evaluation of loan portfolio quality (good vs bad loans)
• Analysis of borrower characteristics and risk factors
• Identification of funding trends across time and loan segments

## Tools & Technologies

• SQL – Data exploration and validation
• Python – Data preparation and preprocessing
• Microsoft Power BI – Dashboard development and visualization
• DAX – KPI calculations and financial metrics
• Data Modeling – Relationship design for loan datasets

## Key Metrics Tracked

• Total Loan Applications
• Total Funded Amount
• Total Amount Received
• Average Interest Rate
• Month-to-Date (MTD) Lending Performance
• Good vs Bad Loan Distribution

## Dashboard Features

### Portfolio Summary

High-level view of total loan applications, funding volume, repayment amounts, and interest rate trends.

### Loan Quality Analysis

Loans are segmented into good and bad loan categories to evaluate overall portfolio risk and repayment behavior.

### Borrower Profile Analysis

Loan funding is analyzed by borrower attributes such as employment length and home ownership.

### Geographic Distribution

Loan issuance trends are visualized geographically to identify regional lending concentration.

### Funding Trends

Monthly funding analysis helps track lending growth and detect changes in funding activity.

### Loan Term Analysis

Comparison between short-term (36 months) and long-term (60 months) loans to understand portfolio composition.

## Key Insights

• Debt consolidation loans represent the largest share of funded loans.
• Borrowers with shorter employment history show higher default probability.
• 60-month loans carry higher risk compared to 36-month loans.
• Loan issuance increased significantly in Q3 indicating seasonal demand.

## Business Value

The dashboard enables financial analysts and lending teams to:

• Monitor portfolio health in real time
• Identify potential credit risk patterns
• Evaluate borrower segments with higher loan volumes
• Track lending growth and funding allocation

By transforming loan data into interactive insights, this solution supports data-driven lending and risk management decisions.

## Repository Structure

data/ – loan dataset used for analysis
dashboard/ – Power BI dashboard (.pbix file)
images/ – dashboard screenshots
insights.md – key portfolio insights derived from analysis
