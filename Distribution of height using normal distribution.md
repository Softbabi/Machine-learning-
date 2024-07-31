#Practical 2: Distribution of height using normal distribution

import numpy as np

import matplotlib.pyplot as plt

#Parameters for normal distribution

mean_height=170 #mean height in cm

std_dev_height = 10 # standard deviation in cm

num_samples = 1000

#Generate synthetic height data heights. np.random.normal(loc=mean_height, scale=std_dev_height, size=num_sample

MANASE

#Plot the distribution

plt.hist(heights, bins-30, density-True, alpha=0.6, color 'green', edgecolor='black')

plt.title('Distribution of Heights')

plt.xlabel('Height (cm)')

plt.ylabel('Density')

plt.show()
