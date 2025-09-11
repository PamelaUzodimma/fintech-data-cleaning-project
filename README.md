# fintech-data-cleaning-project

## Project Purpose
This project focuses on **cleaning and analyzing a financial transactions dataset** using Microsoft Excel.  
The goal is to simulate real-world fintech data preparation tasks — ensuring data quality, uncovering insights, and making the dataset useful for business decision-making.

## Tools
- **Excel**: For data cleaning, transformations, pivot tables, and visualization.
- **GitHub**: For project version control and portfolio showcase.

## Dataset
The dataset contains simulated financial transactions, including:
- Transaction IDs
- Account IDs
- Transaction dates
- Transaction types (debit/credit)
- Merchant IDs
- Transaction amounts
- Balances

The raw dataset is included as `original_dataset.csv`.

## Problem Statement

Upon reviewing the raw transactions dataset, the following data quality issues were observed:

1. **Missing values**
   - Some `customer_id` and `description` fields are blank.

2. **Inconsistent formats**
   - The `date` field may not be stored uniformly (some entries are text instead of Excel-recognized dates).
   - The `type` field has inconsistent capitalization (e.g., "Credit", "CREDIT", "credit").

3. **Potential outliers**
   - Some transaction `amount` values are unusually large compared to the majority.
   - Zero or negative amounts (if any) may require further validation.

These issues must be cleaned before meaningful financial insights (such as customer spending behavior and transaction trends) can be extracted.



