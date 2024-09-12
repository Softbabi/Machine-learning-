# write a python program to print the coefficient value of the regression

import numpy as np
from sklearn.linear_model import LinearRegression

# Data
x = np.array([[1], [2], [3], [4], [5]])
y = np.array([2, 4, 6, 8, 18])

# Create and fit the model
model = LinearRegression()
model.fit(x, y)

# Get coefficients and intercept
coefficients = model.coef_
intercept = model.intercept_

# Print results
print("Coefficients:", coefficients)
print("Intercept:", intercept)
