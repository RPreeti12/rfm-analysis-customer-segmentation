# rfm-analysis-customer-segmentation
I have executed RFM (Recency, Frequency, Monetary) analysis project for customer segmentation using Python and pandas. Helps identify high-value, loyal, and at-risk customers from sales data.
---

## Dataset Used
[Dataset of sales](sales_data.csv)
-Order information (OrderNumber, OrderDate, _CustomerID)
-Product and pricing details (Unit Price, Unit Cost, Discount Applied, Order Quantity)
-Calculated metrics like Revenue

---
###  Sample RFM Output
![sample output.jpg](https://github.com/RPreeti12/rfm-analysis-customer-segmentation/blob/main/sample_output.png)
## What is RFM?
-Recency – How recently a customer made a purchase
-Frequency – How often a customer makes a purchase
-Monetary – How much money a customer spends

# Project Workflow
-Load and clean data
-Calculate Revenue per order
-Select relevant columns for RFM
-Group by Customer ID and compute:
-Recency (days since last order)
-Frequency (number of orders)
-Monetary (total revenue)
-Create an RFM table for customer segmentation

