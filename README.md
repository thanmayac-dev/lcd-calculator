# lcd-calculator
#Arduino LCD Calculator
#Description

This project is a simple calculator built using an Arduino and a 16x2 LCD display. The user enters two numbers and an arithmetic operator through the Serial Monitor. The result is then displayed on the LCD screen.

#Features
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Displays the calculation and result on a 16x2 LCD
User-friendly prompts through the LCD

#How It Works
The LCD prompts the user to enter the first number.
The user enters the number through the Serial Monitor.
The LCD prompts for the second number.
The user enters the second number.
The LCD asks for an operator (+, -, *, /).
The Arduino performs the calculation.
The expression and result are displayed on the LCD.
A "Thank you" message is shown before the calculator resets for the next calculation.

#Code Highlights
Uses the LiquidCrystal library for LCD communication.
Uses Serial.parseFloat() to read decimal numbers.
Supports basic arithmetic operations.
Displays results directly on the LCD screen.
