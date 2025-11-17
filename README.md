# HEALTHIQ – Fitness & Nutrition Assistant

Description

HEALTHIQ is a fitness and nutrition assistant that helps users calculate important health metrics such as BMR, TDEE, BMI, calorie needs, macronutrients, and also provides personalized meal plans based on their dietary preferences.
The project uses a C-based DLL for performing all calculations and a Streamlit GUI built in Python for a smooth, interactive user experience.

Features

Calculate Basal Metabolic Rate (BMR)

Compute Total Daily Energy Expenditure (TDEE) using activity level

Adjust daily calories according to goals: lose, gain, or maintain weight

Calculate Body Mass Index (BMI)

Generate daily macronutrient breakdown (carbs, protein, fats)

Provide meal plans for different dietary preferences

Smooth and visually attractive Streamlit GUI


Technologies Used

C (DLL)

Used for all backend calculations

Functions for BMR, TDEE, BMI, calories, macros, meal plans


Python 3.x

Streamlit for user interface

ctypes for loading and calling DLL functions


Streamlit

GUI development

User input forms and result display


HTML/CSS (inside Streamlit)

Custom styling

Gradient backgrounds

Card designs & animated headings



How to Run

1. Compile C code to create the DLL file (e.g., project3.dll).


2. Place the DLL in a known directory (update the Python file path accordingly).


3. Install required Python libraries:

pip install streamlit


4. Run the Streamlit app:

streamlit run yourfile.py


5. Fill the form with your age, gender, weight, height, activity level, dietary preference, and fitness goal.


6. Click “Generate My Fitness Plan” to view complete results
   

Author
Kashaf Mehmood - CT-104, 
Waniya Khan - CT-117, 
Kirpa kumari - CT-102, 
Humna shahid - CT-105 
