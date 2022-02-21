# BSAN-6060-CA03
# Keren Shen
# First click on the "census_data.csv" and "Tree Tuning Cases" to download the data.
# Then click on the "CA03 -- KEREN SHEN.ipynb".
# Next, click "Raw" which is located on the right hand side of the cell next to "Blame".
# This action will bring you to a page that looks like the screenshot below. Right click and select "Save As..." to save as a .py.
# Once the code is saved as a .py, it can be opened with BBEdit on a Mac or another text editor software.


#Import Packages

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn import metrics
from category_encoders import OrdinalEncoder
from sklearn.tree import export_graphviz
from six import StringIO  
from IPython.display import Image  
import pydotplus
import graphviz
import os
from sklearn.metrics import confusion_matrix
from sklearn.metrics import classification_report
from sklearn.metrics import roc_curve, auc
from sklearn.model_selection import GridSearchCV
from sklearn.tree import DecisionTreeRegressor
from sklearn import metrics
