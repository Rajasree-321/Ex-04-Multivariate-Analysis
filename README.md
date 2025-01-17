# Ex-04-Multivariate-Analysis
# AIM
 To perform Multivariate EDA on the given data set.
# EXPLANATION
 Exploratory data analysis is used to understand the messages within a dataset. This technique involves many iterative processes to ensure that the cleaned data is further sorted to better understand the useful meaning.The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
# ALGORITHM
 ## STEP 1
Import the built libraries required to perform EDA and outlier removal.
## STEP 2
Read the given csv file
## STEP 3
Convert the file into a dataframe and get information of the data.
## STEP 4
Return the objects containing counts of unique values using (value_counts()).
## STEP 5
Plot the counts in the form of Histogram or Bar Graph.
## STEP 6
Use seaborn the bar graph comparison of data can be viewed.
## STEP 7
Find the pairwise correlation of all columns in the dataframe.corr()
## STEP 8
Save the final data set into the file

# CODE

import pandas as pd

import seaborn as sns

import numpy as np

import matplotlib.pyplot  as plt

df=pd.read_csv("/content/SuperStore.csv")

df.head()

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/4b5c68e0-895a-4bda-9553-7f6085e2f98d)

df.info()

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/279910ef-7154-4d40-b760-e576017a0216)

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/a670f50a-9e9c-4328-b2f1-7d3ea6544c43)


# OUTPUT

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/2889f267-2495-4d93-9752-7eea5247c292)

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/bae7a291-8bed-43b8-ba59-141f3d7dec92)

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/ba0635b9-f61d-4f22-ac97-886793f34db9)

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/7418ca5d-c82f-47f6-aac8-745b435e2aad)

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/b7875902-430e-4360-be24-6c4d774acf2d)

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/bda5a740-3d19-483f-920d-7af830470519)

![image](https://github.com/Rajasree-321/Ex-04-Multivariate-Analysis/assets/96918911/7b02d5ce-b6d6-4dbd-8bc1-fd8b43cb0036)


# RESULT
Thus the program to perform EDA on the given data set is successfully executed.


