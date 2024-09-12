# write python program to print the import matplotlib.pyplot as plt
from scipy import stats

# Data
x = [5, 7, 8, 7, 2, 17, 2, 9, 4, 11, 12, 9, 6]
y = [99, 86, 87, 88, 111, 86, 103, 87, 94, 78, 77, 85, 86]

# Perform linear regression
slope, intercept, r, p, std_err = stats.linregress(x, y)

# Function to predict speed
def predict_speed(age):
    return slope * age + intercept

# Predict speed for a 5-year-old car
predicted_speed = predict_speed(5)
print(f'Predicted Speed for a 5-year-old car: {predicted_speed:.2f} units')

import matplotlib.pyplot as plt
from scipy import stats

# Data
x = [5, 7, 8, 7, 2, 17, 2, 9, 4, 11, 12, 9, 6]
y = [99, 86, 87, 88, 111, 86, 103, 87, 94, 78, 77, 85, 86]

# Perform linear regression
slope, intercept, r, p, std_err = stats.linregress(x, y)

# Function to predict speed
def predict_speed(age):
    return slope * age + intercept

# Predict speed for a 5-year-old car
predicted_speed = predict_speed(5)
print(f'Predicted Speed for a 5-year-old car: {predicted_speed:.2f} units')