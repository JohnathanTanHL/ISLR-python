# Base Template for ML Projects

# Step 1: Load Libraries and dependencies (edit/delete as necessary) 
import pandas as pd 
import numpy as np  
import scipy as sp  
import sklearn as skl 
import matplotlib as mpl  

# Step 2: Load Data
filename = 'filename.csv' 
data = pd.read_csv(filename, nrows=xx, header=None, sep='\t', comment='#', na_values = [""])

# Step 3: Initial Data Exploration
Plot to see how data looks.   
Clean data as neccessary. 
