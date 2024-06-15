# BMI Calculator in Python

This repository contains the code for a basic Body Mass Index (BMI) calculator using Python. This simple application allows users to calculate their BMI by inputting their height (in cm) and weight (in kg).

## Features

- This calculator takes two inputs from the user: height in cm and weight in kg.
- The BMI is calculated using the formula `weight/(height/100)^2`.
- The application then assesses the user's BMI against the following scale:
    - BMI < 16: Severely underweight
    - 16 < BMI < 18.5: Underweight
    - 18.5 < BMI < 25: Normal
    - 25 < BMI < 30: Overweight
    - 30 < BMI < 35: Moderately obese
    - BMI > 35: Severely obese

## How to Use

1. Clone this repository.
2. Make sure you have Python installed on your system.
3. Run the `bmiwebapp.py` script.
4. Enter your height and weight as prompted.

This BMI calculator application was developed as a web app using the **PyWebIO**  library in Python. PyWebIO provides a series of imperative functions to obtain Web input and output, which lets you write web applications as if you were writing terminal programs. Make sure to install the PyWebIO library in your Python environment before running this application.
