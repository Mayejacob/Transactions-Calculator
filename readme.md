# Transactions Discount Calculator

This project reads transaction data from an Excel file, calculates the total and discount for each transaction, and saves the updated data to a new Excel file.

## Features

- Loads transaction data from an existing Excel file (`transactions.xlsx`)
- Calculates the total amount for each transaction by multiplying the unit price and quantity
- Applies a 10% discount to the total amount for each transaction
- Saves the updated data to a new Excel file with a unique filename based on the current date and time

## Requirements

- Python 3.x
- `openpyxl` library

You can install the required library using pip:

```sh
pip install openpyxl
```