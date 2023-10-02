# Analysis-of-BCCI

## project title : Analysis and manuplaction of cricket torniment data set for BCCI ORGINAZATION

# Problem Statement
A panel wants to select players for an upcoming league match based on their 
fitness. Players from all significant cricket clubs have participated in a practice 
match, and their data is collected. Let us now explore NumPy features using th e 
player's data.

Height of the payers is stored as a regular Python list: height_in. The height is expressed in inches.
Weight of the payers is stored as a regular Python list: weight_lb. The weight is expressed in pounds.

# Tools: 
1. Jupyter Notebook.
2. Python Programing Language.
3. Numpy (Python Libery_)
4. Google Colab.

   
# Multiplication with a factor:
Now, let's convert the height and weight of the players into more generic units.
* Height in metres 
* Weight in kilogramsm

# Convert the units of height and weight using appropriate factors (look in the video for the factors)
heights_m = heights_in*0.025
weights_kg = weights_lb*0.45

# Deriving new data from existing:
5. Now, let us try to calculate the Body Mass Index (BMI) value for the players. The formula for BMI is:
Calculate the bmi value based on the formula above
bmi = weights_kg / heights_m**2

# Conclusion :
According to my computation the body mass index for the players the range lies between 23 to 26.
The minimu critera for heights for the height is 23m as individual player.
The maximum criteria for height for the height is 26m as individual player.
