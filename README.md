# Expense Tracker

A simple command-line expense tracking application that helps users manage and analyze their expenses.

## Features

- Add expenses with amount and category
- View all recorded expenses
- Calculate total expenses
- Filter expenses by category

## Installation

```bash
git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker
python expense_tracker.py
```

## Usage

Run the program:
```bash
python expense_tracker.py
```

### Menu Options

1. **Add an expense**: Enter amount and category
2. **List all expenses**: View all recorded expenses
3. **Show total expenses**: Calculate sum of all expenses
4. **Filter expenses by category**: View expenses for specific category
5. **Exit**: Close the program

### Example

```python
# Add an expense
Enter choice: 1
Enter amount: 50.00
Enter category: groceries

# View all expenses
Enter choice: 2
Amount: 50.00, Category: groceries

# Filter by category
Enter choice: 4
Enter category to filter: groceries
Amount: 50.00, Category: groceries
```

## Functions

- `add_expense(expenses, amount, category)`: Add new expense
- `print_expenses(expenses)`: Display all expenses
- `total_expenses(expenses)`: Calculate total sum
- `filter_expenses_by_category(expenses, category)`: Filter by category

## Requirements

- Python 3.x
