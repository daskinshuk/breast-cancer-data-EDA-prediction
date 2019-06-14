# Introduction

In this project the breast cancer data set from UCI Machine Learning repository has been analyzed, 
and a predictive model has been build upon the data. 

[Notebook with Plotly Charts](https://nbviewer.jupyter.org/github/daskinshuk/breast-cancer-data-EDA-prediction/blob/master/breast-cancer-data-analysis.ipynb)

# Data Description

The dataset has been taken from kaggle, the breast cancer dataset is having 31 columns and over 500 entries. 
There are 30 features basd on that the target attribute has to be predicted which is having two values **M** 
for **Malignant** and **B** for **Benign**.

# Libraries used

Several python libraries has been used for this project:

* Pandas
* NumPy
* Scikit-Learn
* Plotly
* Matplotlib
* Seaborn

# Project Description

Fisrt the visual EDA has been done on the data, visualization has been done using python's plotly library. 
The correlation between the attributes has been analyzed, then **Random Forest** algorithm has been used to build the model
and to get the feature importance of the several attributes. Also **PCA** has been used for dimensionality reduction. Finally 
top 10 features has been selected and for classification **Random Forest** and **Gradient Boosing** have been used.
