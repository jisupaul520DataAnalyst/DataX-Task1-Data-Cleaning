# Sales Data Cleaning
A data cleaning and analysis project using real-world sales transaction data.

##Summary

This project demonstrates the full data analytics workflow:
- Data collection and inspection
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)

## 📁 Dataset Description

| Column | Description |
|---|---|
| ID | Unique customer identifier |
| Customer_Name | Name of the customer |
| Order_ID | Unique order reference |
| Order_Date | Date the order was placed |
| Product | Product purchased |
| Category | Product category (Electronics, Books, Sports, Clothing, Home) |
| Quantity | Number of units ordered |
| Price | Unit price |
| Payment_Method | Payment type (Credit Card, PayPal, Cash on Delivery, Bank Transfer) |
| Status | Order status (Delivered, Shipped, Processing, Cancelled, Returned) |
| Total | Total order value |

## 🧹 Data Cleaning Steps Performed (Power Query)

Fixed Negative Quantities — Converted negative values (e.g., -2, -5) to positive using Absolute Value
Filled Missing Categories — Filled down blank/null category cells (nan)
Removed Unnecessary Columns — Dropped columns not needed for analysis
Corrected Date Format — Converted numeric date serials to proper Date format
Replaced Error Values — Cleaned up error cells across Price, Quantity, and Total columns
Filtered Invalid Rows — Removed blank or out-of-scope rows
Fixed Data Types — Ensured each column has the correct type (text, number, date)

## 🛠️ Tools Used
- Microsoft Excel / Power Query

## Folder Structure
```bash
README.md
Sales_Data_Cleaned.xlsx
Sales_Data_Raw.xlsx

Author
Jisu Paul
