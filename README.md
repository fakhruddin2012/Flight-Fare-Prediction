# Flight-Fare-Prediction
## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)
 * [Data Preprocessing](#Data-Preprocessing)
 * [Feature Selection](#Feature-Selection)






## Problem Statement:
This is a Machine learning project. In this project I am trying to predict the fare of flights by training the dataset which contain data for one year. 

## Approach:

## Data Preprocessing:
In this section I am doing all the Data cleaning and analysis.Most of the data is in categorical form which should get converted into numerical form. 

I did some feature engineering in it and created columns of day and months.There are many columns which i created from the existing column which you can see in the notebook.

I dropped the additional info and route columns as most of the values were missing or of no use.

Here is the comparision graph of Airline vs the price.

![image](https://user-images.githubusercontent.com/55452866/103451742-98d52e00-4ced-11eb-92d6-da3f0da4088d.png)

This all the process i followed for test dataset as well and made a training and test dataset to feed in the Machine learning algorithm.

## Feature Selection:

Finding out the best feature which will contribute and have good relation with target variable. Following are some of the feature selection methods.

(1) Heatmap

(2) ExtraTreesRegressor



