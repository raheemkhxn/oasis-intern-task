#OIBSIP_BMI Calculator
This project is a simple BMI Calculator. It allows users to input their weight and height to calculate their Body Mass Index (BMI) and categorize their health status based on the BMI value.

##How It Works:
User Input:

The program prompts users to enter their weight in kilograms and height in meters.
These inputs are then used to calculate the BMI.
Main Functionalities:

1.** BMI Calculation: Computes the BMI using the provided weight and height**.
2.** BMI Category Classification**: Classifies the user into one of four categories based on their BMI**:
Underweight
Normal weight
Overweight
Obesity
Error Handling:

If the user enters non-numeric values for weight or height, the program displays an error message indicating invalid input.
Code Overview:
Functions:

**calculate_bmi(weight, height)**: Calculates BMI using the formula 
BMI
=
weight
height
2
BMI= 
height 
2
 
**weight**
​
  and returns the BMI value.
bmi_category(bmi): Determines the BMI category:
BMI < 18.5: "Underweight"
18.5 <= BMI < 24.9: "Normal weight"
25 <= BMI < 29.9: "Overweight"
BMI >= 30: "Obesity"
###Main Program:

The main() function initiates the program, prompts for user input, and displays the BMI and classification.
Handles invalid input with an error message, ensuring a smooth user experience.

