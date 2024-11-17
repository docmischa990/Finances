# Simple Finance Calculator

This is a Python-based finance calculator designed to help users with basic financial calculations, including calculating expenses, savings, and both simple and compound interest. The program is user-friendly and operates through a command-line interface, allowing users to interact with different financial functions.


## Features
- **Ask for Name**: Greet the user by their name.
- **Calculate Expenses**: Sum up multiple expenses to get the total.
- **Calculate Savings**: Subtract expenses from income to calculate savings.
- **Simple Interest Calculation**: Calculate simple interest based on principal, rate, and time.
- **Compound Interest Calculation**: Calculate compound interest based on principal, rate, times compounded per year, and years.
- **Exit Command**: Allows the user to exit the program gracefully.


## How It Works
The program prompts users to select a command. Based on the selected option, the program will guide users through a series of inputs to perform the chosen financial calculation.


### Available Commands:
- `ask_name`: Greet the user.
- `expenses`: Calculate total expenses.
- `savings`: Calculate total savings by subtracting expenses from income.
- `simple_interest`: Calculate simple interest using a formula.
- `compound_interest`: Calculate compound interest using a formula.
- `exit`: Exit the program.


## Example Usage:

```bash
Which command would you like to run? Options: ask_name, expenses, savings, simple_interest, compound_interest, exit
ask_name
What is your name? John
Hello, John!

Which command would you like to run? Options: ask_name, expenses, savings, simple_interest, compound_interest, exit
expenses
How many expenses do you have? 3
Enter expense 1: 200.50
Enter expense 2: 300.30
Enter expense 3: 400.00
Total expenses: £900.80

Which command would you like to run? Options: ask_name, expenses, savings, simple_interest, compound_interest, exit
savings
What is your total income? 2000000
What are your total expenses? 550000
Total savings: £1450000.00

Which command would you like to run? Options: ask_name, expenses, savings, simple_interest, compound_interest, exit
simple_interest
Enter the principal amount: 1000
Enter the interest rate (in %): 5
Enter the time (in years): 3
Simple interest: £150.00

Which command would you like to run? Options: ask_name, expenses, savings, simple_interest, compound_interest, exit
compound_interest
Enter the principal amount: 1000
Enter the interest rate (in %): 5
How many times per year is the interest compounded? 4
Enter the number of years: 2
Compound interest: £104.09

Which command would you like to run? Options: ask_name, expenses, savings, simple_interest, compound_interest, exit
exit
Exiting the program.
```


## Requirements
Python 3.x or above

##Installation

1. Clone the repository:
   git clone https://github.com/docmischa990/Finances.git
   
2. Navigate to the project directory:
   cd finance-calculator
   
3. Run the script:
   python finance_calculator.py


## Functions Explained
```bash
ask_name():
Asks for the user's name and greets them.
calculate_expenses(expenses):
Takes a list of expenses and returns the sum total.
calculate_savings(income, expenses):
Calculates the savings by subtracting the total expenses from the income.
simple_interest(principal, rate, time):
Calculates simple interest using the formula:
Interest
=
Principal
×
(
Rate
100
)
×
Time
Interest=Principal×( 
100
Rate
​	
 )×Time
compound_interest(principal, rate, times_compounded, years):
Calculates compound interest using the formula:
Amount
=
Principal
×
(
1
+
Rate
100
×
times_compounded
)
times_compounded
×
years
Amount=Principal×(1+ 
100×times_compounded
Rate
​	
 ) 
times_compounded×years
 
Compound Interest
=
Amount
−
Principal
Compound Interest=Amount−Principal
```


## Contributing
Feel free to fork the repository and submit pull requests with any improvements or additional features.


## License
This project is open-source and available under the Apache License.


## Acknowledgements
Developed by Mischa Doctor.
