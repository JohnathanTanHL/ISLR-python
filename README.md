# Base Template for ML Projects

# Step 1: Load Libraries and dependencies (edit/delete as necessary) 
import pandas as pd 
import numpy as np  
import scipy as sp  
import sklearn as skl 
import matplotlib as mpl  
import seaborn as sns

# For Linear Regression
import sklearn.linear_model as skl_lm
from sklearn.metrics import mean_squared_error, r2_score

# For logistic Regression
import sklearn.linear_model as skl_lm
from sklearn.discriminant_analysis import LinearDiscriminantAnalysis
from sklearn.discriminant_analysis import QuadraticDiscriminantAnalysis
from sklearn.metrics import confusion_matrix, classification_report, precision_score
from sklearn import preprocessing
from sklearn import neighbors

# For Basic Model statistics 
import statsmodels.api as sm
import statsmodels.formula.api as smf



# Step 2: Load Data
filename = 'filename.csv' 
data = pd.read_csv(filename, nrows=xx, header=None, sep='\t', comment='#', na_values = [""])

# Step 3: Initial Data Exploration
Plot to see how data looks.   
Clean data as neccessary. 
