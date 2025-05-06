# 📊 Stock Portfolio Dashboard

## 🧾 Introduction

This Excel workbook serves as a dynamic **Stock Portfolio Dashboard** that helps users track, analyze, and visualize their stock investments. It includes key performance indicators (KPIs), portfolio allocation charts, and real-time valuation tracking to support investment decisions.

## 📘 Excel Formulas Used in This File

The following Excel functions and formulas are used throughout the file:

### ➕ Arithmetic & Logical
- `IF()`: Used for conditional checks and outputs.
- `IFERROR()`: Handles errors gracefully by substituting error values with specified results.
- `AND()`, `OR()`: Logical operations to control conditional logic.

### 📈 Financial & Statistical
- `XIRR()`: Calculates the internal rate of return for a schedule of cash flows (extended IRR).
- `SUM()`: Totals numeric values.
- `AVERAGE()`: Computes the mean.
- `COUNTIF()`: Counts cells matching a condition.

### 🔗 Lookup & Reference
- `VLOOKUP()`: Searches for a value in the first column and returns data from another column.
- `INDEX()` + `MATCH()`: Dynamic lookups allowing for flexible row and column references.
- `INDIRECT()`: Converts a text string into a cell reference.
- `OFFSET()`: Returns a reference to a range offset from a starting point.

### 📅 Date & Time
- `TODAY()`: Returns the current date.
- `NOW()`: Returns the current date and time.
- `YEAR()`, `MONTH()`, `DAY()`: Extracts date parts.

### 📊 Dynamic Data & Dashboard
- `SORT()`, `FILTER()`, `UNIQUE()`: Used to build dynamic, auto-updating tables and charts.
- `TEXT()`: Formats numbers and dates into readable strings.
- `CHOOSE()`: Selects a value from a list based on an index number.

## 📁 Sheet Overview

| Sheet Name           | Description |
|----------------------|-------------|
| `Dashboard`          | Visual overview of portfolio performance with KPIs and charts. |
| `Portfolio Data`     | Core dataset including stock symbols, purchase prices, quantities, and current values. |
| `Transactions`       | Chronological list of stock buys/sells, used for performance tracking. |
| `Returns Summary`    | IRR, total return, and dividend tracking calculations. |
| `Lookups`            | Contains reference tables for formulas and dropdowns. |

## 📌 How to Use

1. **Update your holdings** in the `Portfolio Data` sheet.
2. **Record transactions** in the `Transactions` sheet to keep your IRR and gain/loss accurate.
3. View your **performance metrics and visualizations** in the `Dashboard`.
4. Make sure your formulas are updated for any new rows using structured table references.

## 🛠 Requirements

- Microsoft Excel 365 (due to use of dynamic array formulas like `FILTER()` and `SORT()`).
- Internet connection (if live data or add-ins like STOCKHISTORY are being used).
