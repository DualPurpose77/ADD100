"""
-----------------------------------------------------------------------
ASSIGNMENT REQUIREMENTS
-----------------------------------------------------------------------
[ ] 1. Header Docstring included.
[ ] 2. Ask user for Monthly Income (float).
[ ] 3. Ask user for 5 DIFFERENT expense amounts (float).
[ ] 4. Calculate Total Expenses and Remaining Balance.
[ ] 5. Calculate Percentage of Income Spent.
[ ] 6. Output formatted to 2 decimal places (:,.2f).
-----------------------------------------------------------------------
"""

# 1. Header Docstring included!
'''
Assignment: The Personal Budget
Date: 1/27/2026
File: personalbudget.py
'''

# 2. Ask for and convert monthly income into a Float value

income = float(input("How much is your monthly income? "))

# 3. Ask for and convert five expenses into Float values

electric = float(input("How much was spent on Electricity? "))
heat = float(input("How much was spent on Heating? "))
food = float(input("How much was spent on Food? "))
gas = float(input("How much was spent on Gas? "))
entertain = float(input("How much was spent on Entertainment? "))

# 4. Calculate total and remaining amounts with expenses and income

totalexpense = electric + heat + food + gas + entertain
remainder = income - totalexpense 

# 5. Caculate percentage of the income that was spent

percent = totalexpense/income * 100

# 6. Display outputs formatted to 2 decimal places

print(f"You have a monthly income of ${income: ,.2f}")
print(f"Your total amount of expenses come up to ${totalexpense: ,.2f}")
print(f"You spent {percent: .2f}% of your income on expenses. ")
