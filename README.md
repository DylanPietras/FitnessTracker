# FitnessTracker
Personalized fitness program


weight_pounds = 235
inches_height = 67

print("\n\tBODY MASS INDEX CALCULATOR\n\nThis program will calculate your Body Mass Index.\n\nYou will be asked to input your height in inches and your weight in pounds.\n ")
# Since I haven't learned how to process user input yet, I will be using static numbers until
# I learn user inputs.

# Now we convert inches and pounds into their metric units of meters and kilograms
weight_kg = weight_pounds*.453592
height_meters = inches_height*.0254

# Now we use the calculation kg/meters/meters to find the BMI
bmi = weight_kg / height_meters / height_meters

print(f"Your Body Mass Index is: {bmi}.\n")
