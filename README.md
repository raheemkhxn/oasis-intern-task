How It Works:
Main Functionalities:
Calculate BMI: Takes the user’s weight and height as inputs, then calculates and returns the Body Mass Index (BMI).
BMI Category Classification: Based on the calculated BMI, the program classifies the user into one of several categories: Underweight, Normal weight, Overweight, or Obesity.
Code Overview:
Functions:
calculate_bmi(weight, height): Accepts weight (in kilograms) and height (in meters), calculates BMI using the formula 
BMI
=
weight
height
2
BMI= 
height 
2
 
weight
​
 , and returns the result.
bmi_category(bmi): Takes the calculated BMI and returns a category based on the BMI value:
Below 18.5: "Underweight"
Between 18.5 and 24.9: "Normal weight"
Between 25 and 29.9: "Overweight"
30 and above: "Obesity"
Main Program:
The main() function starts the program with a welcome message.
Prompts the user to enter their weight and height.
Calls calculate_bmi to compute the BMI and bmi_category to determine the user’s classification.
Displays the BMI value and corresponding category.
Handles invalid input with an error message.
Usage Example:
Start the Program: The user runs the code, and the program displays a welcome message.
Enter Weight and Height: The user inputs their weight in kilograms and height in meters.
View Results:
The program displays the BMI and the category, such as "Normal weight" or "Obesity," based on the calculated value.
