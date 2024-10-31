# Credit Card Transaction Dashboard Report

## Overview
The dashboard presents an analysis of credit card transaction data, focusing on customer demographics, transaction categories, and revenue metrics.  
The data is imported from SQL Server, with preprocessing done to ensure smooth performance and insightful visualizations.

## Data Source
- **SQL Server Database**: CreditCardReport  
- **Primary Table**: cc_detail, customer_details  
- **Imported Data**: Credit card transaction details from `credit_card.csv`, Customer details from `customer.csv`

## Key Metrics and Visuals
1. **Transaction Volume and Revenue**:  
   - Visuals display **sum of revenue** and **total transaction volume** broken down by **quarter** to track revenue trends over time.

2. **Demographic Breakdown**:  
   - Age groups (e.g., 20-30, 30-40) created using calculated columns allow insights into revenue by different age ranges.  
   - Education and occupation breakdowns to understand the spending behavior of various customer segments (e.g., Graduate, White-collar).

3. **Revenue by Card Category**:  
   - Card categories (e.g., Blue, Gold, Platinum) are analyzed for revenue contribution, transaction volume, and interest earned.  
   - Provides an easy comparison of card performance.

4. **Transaction Type Analysis**:  
   - Visuals for **transaction methods** (Swipe, Chip, Online) highlight revenue based on transaction types.

5. **Weekly Trends**:  
   - Week numbers are calculated to observe transaction patterns by week, which helps identify seasonal and weekly transaction trends.

## Data Processing & Cleaning
- Data cleaning was performed in SQL Server to improve dashboard performance.  
- Additional columns like **Age Group** and **Week Number** were added for refined insights.

## Design and Aesthetics
- The dashboard uses a **blue and black theme** to create a professional look.  
- Background and visuals are designed to be minimalistic, ensuring focus on data insights.

## Final Observations
The dashboard offers a comprehensive overview of customer spending behavior and transaction details.  
The SQL Server integration enables smooth data processing, while Power BI visuals provide actionable insights into customer demographics,  
transaction types, and card category performance.

---

| [Download Transaction Report](https://github.com/user-attachments/files/17589317/Transaction.Report.pdf) | ![Dashboard Image](https://github.com/user-attachments/assets/be7f6ba1-f52f-4a67-833f-bf95cac40ac4) |
|:---:|:---:|
