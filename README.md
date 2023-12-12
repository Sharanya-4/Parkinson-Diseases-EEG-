# Parkison Disease Detection using SVM
# Dataset:
 - This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD).
 - The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording.
 -  The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD.

# Libraries:
 - pandas as pd
 - numpy as np
 - seaborn as sns
 - matplotlib.pyplot as plt
 - sklearn.model_selection

# Explore Data: 
- data.head()
- data.describe()
- data.info()
- data.shape()
- data..isnull().sum()

# Model Training:
 - For Parkinson's Disease, we utilized various machine learning algorithms, with the primary algorithm chosen for its accuracy being Support Vector Machines (SVM).

# Models:
   1. Pickle
   2. Sklearn Joblib
