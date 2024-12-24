# Cash Flow Minimizer System

## Overview

This system minimizes the number of transactions among multiple banks using different payment modes. A world bank acts as an intermediary for banks with no common payment modes.

## How to Use

1. **Compile the Code:**
   ```sh
   g++ -o cash_flow_minimizer main.cpp
   ```

2. **Run the Program:**
   ```sh
   ./cash_flow_minimizer
   ```

3. **Input Details:**
   - Enter the number of banks.
   - For each bank, enter the bank name, number of payment modes, and the payment modes.
   - Enter the number of transactions.
   - For each transaction, enter the debtor bank, creditor bank, and the amount.

## Example

```sh
Enter the number of banks: 3
World Bank: WorldBank 3 PayPal Stripe Visa
Bank 1: Bank1 2 PayPal Visa
Bank 2: Bank2 1 Stripe
Enter number of transactions: 2
0 th transaction: Bank1 Bank2 100
1 th transaction: Bank2 WorldBank 50
```

## Output

```
Bank1 pays Rs 50 to WorldBank via PayPal
Bank1 pays Rs 50 to Bank2 via Visa
```
