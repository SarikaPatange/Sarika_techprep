# Sarika_techprep
This calculator can perform basic arithmetic operations like addition, subtraction, multiplication and division.
It will perform decimal operations.
Clear screen will clear the display screen.
The calculator consists of 
Mathematical operators: addition(+), substraction(-), multiplication(*) and division(/)
Digits and decimal button: 0,1,2,3,4,5,6,7,8,9,.
Display screen: It displays mathematical expression and the result.
Clear screen button: It clears all mathematical values.
Calculate button(=): It evaluate the mathematical expression and returns the result.
In index.html file to create structure of a calculator use <table> tag.
The <table> tag contains five rows which represent five horizontal sections of the calculator.
Each row has a corresponding <tr> tag. Each <tr> tag contains <td> tags which hold the display screen and buttons of the calculator.
In style.css file the .calculator and .display-box class selectors style the table structure 
and the display screen of the calculator respectively.
In script.js file the clearScreen(), display(), and calculate() functions add functionality to the Calculator.
The clearScreen() function clear values by assinging empty string.appends the value of the clicked button to the result.
The display() function appends the value of the clicked button to the result.
The calculate() function evaluates the expression.
