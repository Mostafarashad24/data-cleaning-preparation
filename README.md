# Data Cleaning & Preparation

## Project Overview

This project focuses on cleaning and preparing a retail orders dataset for reliable analysis.

The dataset contains 1,200 records and 14 columns covering order information, customer details, products, quantities, prices, payment methods, order status, tracking information, coupon codes, marketing sources, and total amounts.

The main goal was to identify and resolve data-quality issues and validate that the cleaned dataset is ready for further analysis.

---

## Objectives

The project focuses on:

- Identifying missing values
- Handling missing CouponCode values
- Checking for duplicate rows
- Checking for duplicate OrderIDs
- Validating date values and formats
- Producing a clean and analysis-ready dataset
- Documenting the cleaning and validation process

---

## Dataset

The original dataset contains:

- **Rows:** 1,200
- **Columns:** 14

The dataset includes information such as:

- Order ID
- Order Date
- Customer ID
- Product
- Quantity
- Unit Price
- Shipping Address
- Payment Method
- Order Status
- Tracking Number
- Delivery Days
- Coupon Code
- Marketing Source
- Total Amount

---

## Data Cleaning Process

### 1. Missing Values

The dataset contained missing values in the `CouponCode` field.

These missing values were replaced with:

`No Coupon`

After cleaning:

- Missing values: **0**
- Missing CouponCode values: **0**

### 2. Duplicate Rows

The dataset was checked for duplicate rows.

Result:

- Duplicate rows: **0**

### 3. Duplicate Order IDs

The `OrderID` field was checked to ensure that each order had a unique identifier.

Result:

- Duplicate OrderIDs: **0**

### 4. Date Validation

Date values were checked to identify invalid, missing, or incorrectly formatted dates.

Result:

- Invalid/missing dates: **0**
- Incorrectly formatted / unparseable dates: **0**

---

## Validation Results

| Validation Check | Result | Status |
|---|---:|---|
| Missing values after cleaning | 0 | PASS |
| Duplicate rows | 0 | PASS |
| Duplicate OrderIDs | 0 | PASS |
| Incorrectly formatted / unparseable dates | 0 | PASS |

---

## Project Files

### `data/raw/`

Contains the original dataset before cleaning.

### `data/cleaned/`

Contains the cleaned dataset used for further analysis.

### `Data_Analytics_Project1_Cleaned.xlsx`

The final Excel workbook also contains:

- README
- Raw Data
- Cleaned Data
- Cleaning Report
- Evidence

---

## Tools

- Microsoft Excel
- Data Cleaning & Validation

---

## Outcome

The final dataset passed all required data-quality checks and is ready to be used for further data analysis.

The cleaned data contains:

- 1,200 rows
- 14 columns
- 0 missing values
- 0 duplicate rows
- 0 duplicate OrderIDs
- 0 invalid/unparseable dates
