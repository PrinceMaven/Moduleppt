# Exploratory Data Analysis on Iris Flower Dataset

## Content of my project

Introduction 
Task to be done
Steps to perform EDA
EDA Flowchart
Dataset
Library used
Code Structure
Code snippet
Visualization of different varieties of Iris
Summary



## Introduction


Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods. It helps determine how best to manipulate data sources to get the answers you need, making it easier for data scientists to discover patterns, spot anomalies, test a hypothesis, or check assumptions.

## Task to be done:


I have done the Exploratory Data Analysis of the famous Iris dataset and tried to gain useful insights from the data. The features present in the dataset are:
Sepal Width
Sepal Length
Petal Width
Petal Length

## Steps to perform EDA



Gathering dataset and preliminary processing of data.
Check total number of entries and column types
Check any null values
Check duplicate entries
Plot distribution of numeric data (univariate and pairwise joint distribution)
Plot count distribution of categorical data
Analyse the different  frequencies of varieties of given dataset

## Dataset


Source Dataset : Iris (Taken from Kaggle)
The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository.



## Library used


Numpy
	 for numerical array and mathematical statistical calculations
Pandas
	 high level fast, powerful, flexible and easy to use open source data analysis and manipulation tool
Matplotlib
	Visualization using Matplotlib generally consists of bars, pies, lines, scatter plots.
Seaborn
	provides a variety of visualization patterns



## Code Structure

 
### Module on explodatory Data Analysis on iris flower


#### Importing Libraries


``` import numpy as np  
import pandas as pd  
import seaborn as sns  
import matplotlib.pyplot as plt 
``` 


#### Reading/ Loading Dataset

Dataset taken from kaggle or uci too Dataset name: iris.csv https://www.kaggle.com/uciml/iris?select=Iris.csv



```  data = pd.read_csv('iris1.csv') 
```






## Output

Visualizations of different varieties of iris
Sepal length and width
Petal length and width

## Summary


Used Iris dataset has equal frequencies  i.e. equal records are present for all three species.
There was four numerical columns while just one categorical column which in turn is our target column and one unnamed was unwanted so we attempt feature selection by dropping it.
I have visualised the correlation between petal width and petal length using seaborn and matplotlib
Versicolor and Virginica species are usually mixed and are sometimes hard to separate, while usually Versicolor has average feature sizes and virginica has larger feature sizes.
Setosa variety  is the easily distinguishable as it has small size.  


## Conclusion 

Observation from the visualizations:
 if 0≤petal_length≤2 and 0≤petal_width≤0.7then setosa
 if 2≤petal_lenght≤5.2 and 1≤petal_length≤1.7 then versicolor
 else virginica


## Next Steps

Applying model and algorithm
Decision making
Finding accuracy and precision score.

























