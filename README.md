# loan_analyzer

This is a Python program that automates the tasks associated with valuing microlending loans.

## GitHub Repo

All work has been saved onto my github repo: https://github.com/jjestrella/loan_analyzer

## Part 1: Automating Loan Calculations

Loops and variables are used to automate the calculations for the loan portfolio summaries. 
1. Use the `len` function to calculate the total number of loans in the list.

2. Use the `sum` function to calculate the total of all loans in the list.

3. Using the sum of all loans and the total number of loans, calculate the average loan price.

4. Print all calculations with descriptive messages and rounded 2 decimal spaces.

## Part 2
This is where we determine the investment evaluation by calculating the present value, or fair price, of what this loan would be worth. 

The goal is to determine if it makes sense to buy the loan at its current price. By present value representing the loan's fair value (given the required minimum return of 20%).

## Part 3
create a financial function that can be reused with new data values.

 ## Part 4
 
 Conditionally Filtering the loan list. Accomplished by looping through a series of loans that the company is considering and filter them to find the inexpensive ones.

 ## Part 5

Finally we create a CSV File output of our list of inexpensive loans.  Using Python's csv library to create the `csvwriter` for this task