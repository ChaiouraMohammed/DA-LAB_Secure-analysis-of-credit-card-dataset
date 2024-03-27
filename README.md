# Data_analysis_Secure-analysis-of-credit-card-dataset
The purpose of this lab is to make a preliminary data analysis in a security area based on a credit card clients dataset with helping frameworks &amp; libraries in Python.

## Well well so ... Why choosing this Lab ?
1.  Explore the credit card clients dataset and calculate the main statistical indicators.
2.  Build different dependencies among the existing attributes of the dataset.
3.  Visualize the data analysis results with various plot types.
## Questions to ask about this Dataset
We will try to give answers to a set of questions that may be relevant when analyzing credit card clients' data : 
1.  What is the average age of all the clients?
2.  What part of clients out of the whole set has an issue with the default payment in the next month?
3.  How many clients are married and single?
4.  What are percent proportions for non-unique values of the variables?
5.  Which are the values with very high dependences among all the features based on the full correlation matrix?
6.  How can we identify new trends in a client's operations roadmap?
7.  How can we define the boundaries (where most data points are tightly concentrated) for the feature pairs?
8.  What is the share of clients in our DataFrame who are ready for their default payment next month?
9.  What are the mean values ​​of numerical features among the attracted clients (the average age of the clients and the average delay of their repayment status)?
10. What was the average repayment status in September 2005 for a typical client who was going to pay in the next month?
11. What part of clients paid duly in September 2005?

## Libraries to use 
```
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns
```
## Downloading the Dataset 
```
!wget https://archive.ics.uci.edu/ml/machine-learning-databases/00350/default%20of%20credit%20card%20clients.xls
!mv -f 'default of credit card clients.xls' 'CreditCard.xls'
```
## Examples for outcomes visualization 
![image](https://github.com/ChaiouraMohammed/Data_analysis_Secure-analysis-of-credit-card-dataset/assets/91562298/444d346b-dc87-49cd-9969-28cc7c280ef0)

![image](https://github.com/ChaiouraMohammed/Data_analysis_Secure-analysis-of-credit-card-dataset/assets/91562298/402e151e-9eb0-4fc2-9228-6f3132cd4320)

