📊 Dataset Information

## Overview

This dashboard is built using a large-scale Financial Transactions dataset containing over **13 million transaction records**. The dataset represents customer spending behavior, payment methods, merchant information, and demographic attributes.

The data was transformed and modeled in **Power BI** using Power Query, DAX measures, and a star schema to generate meaningful business insights.

---

## Dataset Highlights

| Attribute | Details |
|----------|---------|
| Total Records | 13+ Million Transactions |
| Customers | 1,000+ |
| Revenue | $571.84 Million |
| Time Period | Multiple Years |
| Dashboard Pages | 3 |
| Data Model | Star Schema |

---

## Main Tables

The dashboard uses the following tables:

- **Fact_Transactions**
  - Transaction Amount
  - Card Type
  - Merchant Details
  - Transaction Date

- **Dim_Customers**
  - Age Group
  - Gender
  - Credit Score
  - Income
  - Number of Credit Cards
  - Retirement Age

- **Dim_MerchantCategory**
  - Merchant Category
  - Merchant City
  - Merchant State

---

## Key Fields Used

| Field | Description |
|------|-------------|
| amount | Transaction amount |
| gender | Customer gender |
| age_group | Customer age category |
| credit_score | Customer credit score |
| per_capita_income | Customer income level |
| merchant_category | Type of merchant |
| merchant_city | Merchant location |
| merchant_state | Merchant state |
| card_brand | Visa, Mastercard, Amex, Discover |
| card_type | Credit, Debit, Debit (Prepaid) |
| use_chip | Swipe, Chip, Online |

---

## Data Preparation

The dataset was cleaned and transformed using **Power Query**, including:

- Removing unnecessary columns
- Handling missing values
- Creating calculated columns
- Creating Income Groups
- Formatting data types
- Building relationships between tables

---

## DAX Measures

Some of the key DAX measures used include:

- Total Revenue
- Total Transactions
- Total Customers
- Average Transaction
- Revenue by Customer Segment
- Revenue by Merchant Category

---

## Dashboard Features

- Executive KPI Cards
- Customer Analysis
- Transaction Analysis
- Interactive Filters & Slicers
- Drill-down Analysis
- Cross-filtering between visuals
- Multi-page Navigation

---

## Dataset Source

**Source:** Financial Transactions Dataset (Kaggle)
  Link: https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets?utm_source=chatgpt.com

Due to GitHub's file size limitations and dataset licensing, the original dataset is **not included** in this repository.

You can obtain the dataset from Kaggle or use a similar financial transactions dataset to explore the dashboard.

---

## Note

This repository is intended for educational and portfolio purposes. The dashboard demonstrates data modeling, DAX calculations, Power Query transformations, and interactive business intelligence reporting using Microsoft Power BI.
