# CA03: Decision Tree Algorithm
This is an email spam classifier that uses the Gaussian Naive Bayes model.

**Data Overview** <br />
The datset is obtained from the Census Bureau with the salaries of people that are categorized as less than 50k or more than or equal to 50k. These people are categorized by numerous demographic variables, including age, capital gain/loss, education, hours worked per week, marriage status and relationship, occupation, and race and sex.

## Steps 
1. Data Quality Anaysis 
2. Data Cleaning
3. Exploratory Data Analysis
4. Build Decision Tree Classifier Models
5. Vizualize Deicison Tree Using GraphViz
6. Evaluate Decision Tree Performance 
7. Tune Decision Tree Performance 
8. Automate Performance Tuning 
9. Create prediction using trained Decision Tree Model
10. Conclusion

## Packages 
import pandas as pd <br />
import numpy as np <br />
import matplotlib.pyplot as plt <br />
from sklearn.impute import SimpleImputer <br />
from sklearn.preprocessing import LabelEncoder <br />
from sklearn.tree import DecisionTreeClassifier <br />
from sklearn.externals.six import StringIO <br />
from IPython.display import Image <br />
from sklearn.tree import export_graphviz <br />
import pydotplus <br />
from sklearn.metrics import confusion_matrix, accuracy_score, precision_score, f1_score, roc_curve, roc_auc_score, recall_score <br />
from scipy.stats import randint <br />
from sklearn.model_selection import RandomizedSearchCV <br />
from datetime import datetime <br />

## Author
[Karina Ramirez](https://github.com/kramire8 )

## Contributors 
This project was provided by Dr. Arin Brahma at Loyola Marymount University for the Intro to Machine Learning course. <br />
