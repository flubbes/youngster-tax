# Functionality Overview

## Objects
- Taxpayer (Child)
- Government (Parent)
- Expense
- PocketMoney

A Taxpayer creates zero or more Expenses.
An Expense is created by a single Taxpayer.

A Government maintans zero or more Taxpayers.
A Taxpayer is maintained by one or more Government.

A Government rates zero or more Expenses.
An Expense is rated by a single Government.

PocketMoney is created by a single Government.
A Government creates zero or more PocketMoney.
