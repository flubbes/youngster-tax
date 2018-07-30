# Functionality Overview

## Features
- Grant reoccurring (Every Monday, Every X of the month) pocketmoney to children.
- Accept a tax declaration from the child.
- Set tax declaration deadlines (In days).
- The child can create Expenses for a tax delaration.
- The parent can deny a tax declaration if an expense is poorly explained.
- The parent can grant tax repayments per expense if the tax declaration is valid.
- A parent can register at the site
- A parent can create almost infinite

## Objects
- Taxpayer (Child)
- Government (Parent)
- Expense
- Pocketmoney

A Taxpayer creates zero or more Expenses.
An Expense is created by a single Taxpayer.

A Government maintans zero or more Taxpayers.
A Taxpayer is maintained by one or more Government.

A Government rates zero or more Expenses.
An Expense is rated by a single Government.

PocketMoney is created by a single Government.
A Government creates zero or more Pocketmoney Entries.

A Taxpayer receives zero or more Pocketmoney entries.
A PocketMoney entry is granted to a single Taxpayer