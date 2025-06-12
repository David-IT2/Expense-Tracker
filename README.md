
Expense Tracker


**A simple command-line expense tracker application that allows users to add, view, and analyze their expenses.

Features
Add Expenses: Record new expenses with amount and category

View All Expenses: Display all recorded expenses

Calculate Total: Show the sum of all expenses

Filter by Category: View expenses for a specific category

Interactive Menu: Easy-to-use text interface

Usage
Run the program in a Python environment

Use the menu to select an operation:

1: Add a new expense (you'll be prompted for amount and category)

2: List all recorded expenses

3: Show the total of all expenses

4: Filter expenses by category

5: Exit the program

Functions
add_expense(expenses, amount, category): Adds a new expense to the list

print_expenses(expenses): Prints all expenses in a readable format

total_expenses(expenses): Calculates the sum of all expenses

filter_expenses_by_category(expenses, category): Returns expenses filtered by category

main(): Runs the interactive menu loop

Example
text
Expense Tracker
1. Add an expense
2. List all expenses
3. Show total expenses
4. Filter expenses by category
5. Exit
Enter your choice: 1
Enter amount: 25.50
Enter category: Food

Expense Tracker
1. Add an expense
2. List all expenses
3. Show total expenses
4. Filter expenses by category
5. Exit
Enter your choice: 2

All Expenses:
Amount: 25.5, Category: Food
Requirements
Python 3.x

Notes
Expenses are only stored in memory and will be lost when the program exits

No data validation is implemented for the input values


