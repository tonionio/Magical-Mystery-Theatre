# Magical-Mystery-Theatre
The provided JavaScript code implements a basic ticket purchasing system for the "Magical Mystery Theatre." It uses variables, constants, user input, conditional statements, functions, type conversion, string comparison, arithmetic operations, and alerts to determine the appropriate ticket price based on the user's age, student status, and matinee show choice. The code can be easily extended and modified to suit other scenarios and ticket pricing schemes.

## Variables and Constants:
The code uses const to define constants for different ticket prices (GENERAL_ADMISSION, STUDENT, SENIOR, and CHILD) and the matinee discount (MATINEE_DISCOUNT). Variables age and cost are used to store user input and intermediate calculation results.

## User Input:
The script utilizes the prompt() function to collect user input. It asks for the user's age, whether they are a student, and whether it's a matinee show.

## Conditional Statements:
The if...else statements are used to determine the appropriate ticket price based on the user's age and whether they are a student.

## Functions:
The code defines three functions: buyTicket(), matineeDiscount(cost), and getBaseTicketCost(age). Functions allow for better organization and reuse of code.

## Type Conversion:
The user input for age and matinee status is obtained as a string from the prompt() function. The code uses parseInt() to convert the age to a number for comparison.

## String Comparison:
The code uses string comparison to handle the user's input for student status and matinee show.

## Arithmetic Operations: 
The cost of the ticket is calculated using simple arithmetic operations like addition and subtraction.

## Alerts:
The result, i.e., the ticket cost, is displayed to the user using the alert() function.

