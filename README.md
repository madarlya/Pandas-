# 📊 Sales Data Analysis — Python Pandas Project


A hands-on data analysis project using a real-world sales dataset with **185,950 rows** and 6 columns. This project covers the complete basics of data analysis using Python and Pandas — from loading raw data all the way to grouping and aggregation.

---

## 📁 Dataset Overview

| Column | Description |

| Order ID | Unique ID for each order |
| Product | Name of the product ordered |
| Quantity Ordered | Number of units ordered |
| Price Each | Price per unit in USD |
| Order Date | Date and time the order was placed |
| Purchase Address | Full shipping address |

  Total rows:  185,950



## ⚠️ Known Data Issues & Fixes

1. Repeated header rows — column names appear again as data rows because monthly files were merged:

2. Missing values — some rows are completely blank:

3. Wrong data types — Quantity and Price load as text (object):
