# Udacity_DataScience_P1

## Libraries Used (and initial setup code)
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score, mean_squared_error
import seaborn as sns
import statsmodels.api as sm
from pprint import pprint

## Contents of this folder:
 - Readme file:  Has short description
 - Link to my blog post (just the link needed to get to the blog post I wrote from my Jupyter notebook.  (link also shown in text below))
 - Udacity Project 1 Airbnb Seattle Jupyter Notebook (Required for grade)
 - listings.csv (This is the dataset used)


This project utilizes Airbnb Seattle rental property variables (listings excel spreadsheet) from 2016 to predict what types of variables best relate to whether or not a property allows for one night stays.  Logistic regression was utilized as the analytic method of choice.   It was found that the following variables were related to one night availability (with the category that results in more one night stays in parentheses):

- Number of reviews (more)
- Whether a host was a superhost or not (not)
- Whether hosts required a photo of guest or not (not)
- price of rental (lower)
- cancellation policy stringency (less stringent)

## Acknowledgements

 - The original dataset is found at : https://www.kaggle.com/airbnb/seattle/data
 - Code to help me with a Seaborn correlation matrix was found at: https://seaborn.pydata.org/examples/many_pairwise_correlations.html
 - Overlapping Histogram examples were found out at https://datavizpyr.com/overlapping-histograms-with-matplotlib-in-python/
 - Binning help was found at https://stackoverflow.com/questions/45273731/binning-a-column-with-python-pandas
 - Use of Statsmodels for logistic regression was found out at: https://sweetcode.io/easy-scikit-logistic-regression/

## Relevant Personal Links for the Project

 - The blog post is found out at : https://medium.com/@travhao/in-support-of-one-night-stands-c2f565fc65e
 - Repository link is : https://github.com/travhao/Udacity_DataScience_P1
