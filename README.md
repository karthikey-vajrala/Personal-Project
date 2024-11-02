Budget Management Tool
A simple, command-line budget tracker to help you manage your expenses in relation to your salary. This tool allows you to set a salary, add expenses in various categories, and view a detailed summary of spending as a percentage of your income.

Features
Set Salary: Define your monthly salary as a baseline for budgeting.
Add Expense Entries: Log expenses by category and amount.

Display Summary: View a breakdown of spending by category, with amounts and percentages of your salary spent.

Reset Budget: Clear all entries and reset your budget data.



Requirements

Python 3.6 or higher

Tabulate library (for displaying tables in the summary)



Set Up:

1. Open Jupyter Notebook (ipykernel)

2. Install the library by typing into a cell "pip install tabulate" and press shift enter

3. Then in a new cell paste the code given

4. In another cell type "main()" to start using the Budget tracker



Main Menu Options:

When the program starts, you’ll see the following options:


Set Salary: 

Enter your salary amount. This is used to calculate the percentage of salary spent in each category.

Enter your salary as a numeric value.


Add Entry: Add a new expense.

Enter the category name (e.g., "Food", "Rent"):

Enter the amount spent as a number.


Display Summary: 

View the budget summary, which includes:

A table listing each category, total amount spent, and percentage of your salary spent.

A final row showing the total spent across all categories and its percentage of your salary.


Reset Budget: 

Clear all data, resetting both salary and expense entries.


Exit: 

Close the program.

