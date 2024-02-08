# RFM Analysis Project

## Overview

This project conducts RFM (Recency, Frequency, Monetary) analysis using Python. RFM analysis is a customer segmentation technique based on three factors:

- **Recency**: How recently a customer made a purchase
- **Frequency**: How often a customer makes a purchase
- **Monetary**: How much money a customer spends

By analyzing these metrics, businesses can identify valuable customers and tailor marketing strategies.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn

## Installation

Use pip to install the required packages:

```bash
pip install pandas matplotlib seaborn sklearn openpyxl
```

# Usage
1)Clone this repository 
```bash
git clone https://github.com/Balaji-V-S/RFM-Analysis
```

2) Navigate to project folder
```bash
cd rfm_master_code
```

3) Run the .ipynb file

# Data Formats
Ensure your data is in tabular format with these columns:

CustomerID: Unique customer identifier
InvoiceDate: Date of purchase
InvoiceNo: Invoice number
Quantity: Quantity of items purchased
UnitPrice: Price per unit
Revenue: Total revenue (Quantity * UnitPrice)

# Results
After running the script, you'll get:

RFM scores for each customer
Segmentation of customers into categories based on RFM scores
Visualizations like histograms and scatter plots for analysis


