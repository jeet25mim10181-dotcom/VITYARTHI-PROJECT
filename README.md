# VITYARTHI-PROJECT
CLI BMI Calculator: The "Wizard Math" Edition

🎯 Project Overview

This is a fun, highly interactive command-line interface (CLI) tool written in Python that calculates the user's Body Mass Index (BMI). Unlike traditional calculators, this script provides immediate, conversational, and relatable feedback based on the result, using a casual, friendly tone.

The script ensures robustness through detailed input validation for both weight and height, handling non-numerical inputs, commas as decimals, and enforcing realistic physical constraints.

✨ Key Features

Conversational Feedback: Provides unique, informal assessments for each standard BMI category (e.g., "absolute gold zone!", "getting chunky").

Robust Input Validation: Repeatedly prompts the user until valid numerical data for weight (kg) and height (m) is provided within reasonable limits.

Decimal Flexibility: Automatically handles both comma (,) and period (.) as decimal separators.

Re-run Loop: Allows continuous calculations without restarting the script.

🚀 How to Run the Script

Prerequisites

You only need a Python interpreter installed on your system (Python 3.x is recommended).

Steps

Save the Code: Copy the code below and save it to a file named bmi_calculator.py.

Run from Terminal: Open your terminal or command prompt and execute the script:

python bmi_calculator.py

🧠 Core Logic: BMI Calculation

The script uses the standard formula for BMI:

BMI
=
Weight (kg)
Height
2
 (m
2
)

Assessment Breakdown

The script uses the following ranges to generate its fun assessments:

BMI Range

Assessment Message

Health Category (Standard)

<
18.5

Proper skinny / Bit on the slim side

Underweight

18.5
−
24.9

Absolute gold zone!

Healthy Weight

25.0
−
29.9

Carrying a lil extra

Overweight

30.0
−
34.9

Getting chunky

Obesity (Class I)

≥
35.0

Proper heavy / That's a big number

Severe Obesity (Class II/III)

⚠ Disclaimer

This tool is for quick information and entertainment only. The results and conversational assessments are not a substitute for professional medical advice. Please consult a qualified doctor for health concerns.
