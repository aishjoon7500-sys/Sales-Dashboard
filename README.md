# 🛒 Sales Dashboard_1

An interactive Excel dashboard analyzing **1,000 retail sales transactions**, built with PivotTables, PivotCharts, and slicers. The workbook breaks down sales performance across region, state, product category, payment mode, and delivery status.

## Overview

This project turns raw order-level sales data into an interactive dashboard that answers key retail questions:

- Which regions and states drive the most sales?
- Which product categories and sub-categories sell best?
- How do online vs. offline sales channels compare?
- Which payment modes are most popular, and how does delivery status (Delivered, Shipped, Pending, Cancelled) break down?
- How do discounts and profit margins affect net sales and profitability over time?

## Dataset Schema

The `Dataset` sheet contains the following fields:

| Column | Description |
|---|---|
| `Order ID` | Unique identifier for each order |
| `Date` | Order date |
| `Customers Name` | Customer name |
| `Region` | Sales region — East, North, South, West |
| `State` | Indian state (Delhi, Gujarat, Karnataka, Maharashtra, Tamil Nadu, Uttar Pradesh, West Bengal) |
| `Sales Channel` | Online or Offline |
| `Product Category` | High-level category — Electronics, Clothing, Furniture, Groceries |
| `Sub-category` | Specific product line (e.g., Smartphones, Laptops, T-Shirts, Sofas, Snacks) |
| `Quantity Sold` | Units sold in the order |
| `Unit Price` | Price per unit |
| `Total Sales` | Gross sales amount before discount |
| `Discount %` | Discount percentage applied |
| `Discount Amount` | Discount value applied |
| `Net Sales` | Sales amount after discount |
| `Payment Mode` | Cash, Credit Card, Debit Card, Net Banking, or UPI |
| `Delivery Status` | Delivered, Shipped, Pending, or Cancelled |
| `Profit Margin %` | Profit margin percentage |
| `Profit Amount` | Profit earned on the order |

## Dashboard Features

- **16 PivotCharts** (including modern chart types) visualizing sales across region, state, category, payment mode, delivery status, and time
- **13 PivotTables** feeding the dashboard's charts and KPIs
- **Slicers** for interactive filtering by Region, Product Category, Sub-category, Payment Mode, and Delivery Status
- Shared pivot caches ensuring consistent, fast filtering across all views

## Tools Used

- Microsoft Excel — PivotTables, PivotCharts, Slicers

## License

Feel free to use, modify, and share this dashboard for personal or educational purposes.
