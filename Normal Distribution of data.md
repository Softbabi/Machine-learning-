#Practical 2: Normal Distribution of data

import numpy as np

import matplotlib.pyplot as plt

#Parameters for the normal distribution

mean = 0

#Mean of the distribution

std dev = 1 
#Standard deviation of the distribution

num_samples = 100 
#Number of samples to generate

# Generate random samples from a normal distribution 
data = np.random.normal(loc-mean, scale=std_dev, size=num_samples)

#Create a histogram of the data

pli.hist(data, bins=20, density=True, alpha=0.9, color='r', edgecolor='g')

# Add title and labels

plt.title('Histogram of Normally Distributed Data')

plt.xlabel('Value')

plt.ylabel('Density')

# Show the plot

plt.show().

