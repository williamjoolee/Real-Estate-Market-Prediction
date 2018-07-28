# Prediction on Housing Price. 

#### import pandas as pd
import numpy as np
import matplotlib
%matplotlib inline
import seaborn as sns
import mpl_toolkits

sns.set(style="whitegrid", color_codes=True)
sns.set(font_scale=1)
import matplotlib.pyplot as plt
from matplotlib import pyplot as plt

from scipy.stats import norm
from scipy import stats
from scipy.stats import skew
from scipy.stats.stats import pearsonr
import random

from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import RandomForestRegressor, GradientBoostingClassifier
from sklearn.preprocessing import StandardScaler
from sklearn.preprocessing import LabelEncoder
from sklearn import datasets, linear_model
from sklearn.model_selection import train_test_split
import sklearn
from sklearn.linear_model import LinearRegression, LogisticRegression
#from sklearn.datasets import load_

from keras.layers import Dense
from keras.models import Sequential
from keras.regularizers import l1
