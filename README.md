BMI Calculator
A simple web application to calculate Body Mass Index (BMI) using Python and PyWebIO.

Description
This application allows users to input their height in centimeters and weight in kilograms, and then calculates their BMI. The application also provides a textual interpretation of the BMI value according to standard BMI categories.

Features
User-friendly interface for inputting height and weight
Calculates BMI based on user input
Provides a categorization of BMI (e.g., Underweight, Normal, Overweight, etc.)
Requirements
Python 3.x
PyWebIO
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/bmi-calculator.git
Navigate to the project directory:

bash
Copy code
cd bmi-calculator
Install the required packages:

bash
Copy code
pip install pywebio
Usage
Run the application using the following command:

bash
Copy code
python bmi_calculator.py
The application will prompt you to enter your height (in cm) and weight (in kg). After entering the values, it will display your BMI and the corresponding category.

Code Explanation
The main script bmi_calculator.py contains the following:

Input Section: Prompts the user to enter height and weight.
Calculation Section: Calculates BMI using the formula:
BMI
=
weight (kg)
(
height (cm)
100
)
2
BMI= 
( 
100
height (cm)
​
 ) 
2
 
weight (kg)
​
 
Output Section: Displays the BMI value and its interpretation based on predefined categories.
Example
When you run the application, it will look something like this:

yaml
Copy code
Please enter the height in cm: 170
Please enter the weight in Kg: 65
Your BMI is : 22.5 and the person is : Normal
