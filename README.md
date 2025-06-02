## Task 1 – Temperature Conversion Tool
# Overview
This project is a Python-based temperature conversion tool developed as part of Task 1 for the internship program at Prodigy Technologies. The script provides precise conversions between Celsius, Fahrenheit, and Kelvin, and is designed with simplicity, clarity, and modularity in mind.

# Features
Converts temperature values between:

~ Celsius → Fahrenheit & Kelvin

~ Fahrenheit → Celsius & Kelvin

~ Kelvin → Celsius & Fahrenheit

~ User-friendly command-line interface

~ Input validation for numeric values and supported units

~ Clean and formatted output

~ Written using standard Python libraries (no external dependencies)

# Usage
Requirements
~ Python 3.x installed on your system

# Running the Program
~ Download or clone this repository

~ Open a terminal in the project directory

~ Run the script using:
  python task1.py

# Follow the prompts:

~ Enter a temperature value (e.g., 98.6)

~ Specify the unit (Celsius, Fahrenheit, or Kelvin)

Example:
Enter the temperature value: 100
Enter the unit (Celsius, Fahrenheit, Kelvin): Celsius
100.0°C = 212.00°F = 373.15K

# Conversion Logic
The program uses standard scientific formulas for temperature conversion:

| Conversion           | Formula                    |
| -------------------- | -------------------------- |
| Celsius → Fahrenheit | (°C × 9/5) + 32            |
| Celsius → Kelvin     | °C + 273.15                |
| Fahrenheit → Celsius | (°F - 32) × 5/9            |
| Fahrenheit → Kelvin  | ((°F - 32) × 5/9) + 273.15 |
| Kelvin → Celsius     | K - 273.15                 |
| Kelvin → Fahrenheit  | ((K - 273.15) × 9/5) + 32  |

# File Information
task1.py – The main Python script that performs all temperature conversions.

# Author
A. Kovardhini
B.Sc. Computer Science with Artificial Intelligence
Intern, Prodigy Technologies
📧 a.kovardhini1410@gmail.com
