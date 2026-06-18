# Amazon Sales Performance Analysis

Analyzed Amazon sales data using Python to identify factors contributing to loss-making transactions and uncover profitability patterns across products, categories, and regions.

## Project Overview

This project analyzes Amazon sales data to evaluate profit performance, identify loss-generating products, and understand factors associated with negative profit transactions.

Using Python for data preparation, statistical analysis, and visualization, the project aims to provide insights that support profitability improvement.

## Business Questions

1. How is profit distributed across Amazon transactions?
2. Which categories and products contribute most to profit losses?
3. Which states experience the highest losses?
4. How do Sales, Quantity, and Production Cost (HPP) relate to profit performance?

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

## Dataset Information

- Dataset: Amazon Sales Dataset
- Source: Kaggle
- Total Records: 3,203
- Total Features: 10

## Data Preparation

The following preprocessing steps were performed:

- Duplicate checking
- Missing value validation
- Data type conversion
- Outlier detection using IQR
- Feature engineering (HPP & Total Sales)
- Geography column splitting
- Data transformation and encoding

## Key Findings

- 90.1% of transactions generated profit, while 9.9% (318 transactions) resulted in losses.
- Tables, Machines, and Bookcases contributed the highest total losses.
- Lexmark MX611dhe Monochrome Laser Printer recorded the largest product loss (-3,399.98).
- Colorado (-8,901) and Arizona (-6,657) experienced the highest regional losses.
- Production Cost (HPP) showed the strongest negative correlation with Profit (-0.86).

## Business Recommendations

- Re-evaluate high-loss categories and products.
- Prioritize monitoring of high-risk regions such as Colorado and Arizona.
- Optimize production costs (HPP) to improve profitability.
- Develop an early warning system for loss-making transactions.

## Repository Structure

```text
amazon-sales-performance-analysis
│
├── data/
├── notebook/
└── report/
```

## Author

Rafif Pradipta Bagaskara

Data Analyst Portfolio Project
