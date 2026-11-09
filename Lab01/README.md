Python Lab 1 – Semester 5

Student Name: Yukti Patle
Subject: Python Programming Lab
Lab: 1

1. Variable and Identifier Practice

Aim: To declare variables of different data types and display their values and types.

Logic: Four variables are created for name, age, height and student status. The type() function displays the data type of each variable.

Sample Input: No input required.

Sample Output:

Name: Yukti <class 'str'>
Age: 20 <class 'int'>
Height: 1.6 <class 'float'>
Student: True <class 'bool'>

2. Greeting Program

Aim: To accept the user's name, age and city and display a greeting.

Logic: The program accepts three inputs and uses an f-string to combine them into one sentence.

Sample Input:

Name: Yukti
Age: 20
City: Indore

Sample Output:

My name is Yukti, I am 20 years old, and I live in Indore.

3. Arithmetic Operations

Aim: To perform basic arithmetic operations.

Logic: Two numbers are accepted from the user. Addition, subtraction, multiplication, division and remainder are calculated using arithmetic operators.

Sample Input:

10
3

Sample Output:

Sum: 13.0
Difference: 7.0
Product: 30.0
Quotient: 3.3333333333333335
Remainder: 1.0

4. Celsius to Fahrenheit

Aim: To convert Celsius temperature into Fahrenheit.

Logic: The Celsius temperature is accepted from the user and converted using the formula F = (C × 9/5) + 32.

Sample Input:

25

Sample Output:

Temperature in Fahrenheit: 77.0

5. String Manipulation

Aim: To perform different string operations on a full name.

Logic: The program uses upper(), lower(), title(), slicing and len() functions to manipulate the string.

Sample Input:

Yukti Patle

Sample Output:

Uppercase: YUKTI PATLE
Lowercase: yukti patle
Reversed: eltaP itkuY
Length: 11
Title Case: Yukti Patle

6. Escape Sequence Practice

Aim: To print a receipt using escape sequences.

Logic: The program uses \t for tab spacing and \n for a new line to display a receipt.

Sample Input: No input required.

Sample Output:

------ RECEIPT ------
Item        Price
Notebook    50
Pen         10
Pencil      5
---------------------
Total       65

7. Optional: Menu Driven Calculator

Aim: To create a calculator that performs four arithmetic operations.

Logic: A while loop displays a menu repeatedly. The user selects an operation and the program performs the selected calculation until Exit is chosen.

Sample Input:

Choice: 1
First number: 8
Second number: 2

Sample Output:

Result: 10.0
Calculator closed.
