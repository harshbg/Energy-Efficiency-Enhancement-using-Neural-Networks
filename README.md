# Project Name
> This study looked into assessing the heating load and cooling load requirements of buildings (that is, energy efficiency) as a function of building parameters.
The project was done as part of Machine Learning class at the University of Texas at Dallas.
The entire summary of the project can be found in the [Jupyter Notebook](https://github.com/harshbg/Energy-Efficiency-Enhancement-using-Neural-Networks/blob/master/Energy%20Efficiency%20Analysis%20.ipynb)

## Table of contents
* [General info](#general-info)
* [Technologies and Tools](#technologies-and-tools)
* [Setup](#setup)
* [Process](#process)
* [Code Examples](#code-examples)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

The goal of the study is to understand various machine learning classification algorithms and their performance. 
We have added the cooling load and heating load, which can define the overall load of the apartment. We have studied the trend of overall load by dividing it into three classes. 

## Technologies and Tools
* Python 3.5
* TensorFlow

## Setup

The dataset used and its metadata can be found in the [dataset](). 
The jupyter notebook can be downloaded [here](https://github.com/harshbg/Energy-Efficiency-Enhancement-using-Neural-Networks/blob/master/Energy%20Efficiency%20Analysis%20.ipynb) and can be used to reproduce the result. 
Installation of TensorFlow would be required to run all the models. 
You can find the instructions to install TensorFlow in [installation guide](https://www.tensorflow.org/install/pip).

## Process

* We have added the cooling load and heating load which will define the overall load of the apartment. 
* We studied the trend of overall load and divided it into three classes, low efficient, high efficient and average efficient.
* We first tried multioutput machine learning regressor models like KNN, logistic regression, random forest, decision tree, linear & kernalised SVM. 
* After that we created a neural network classification model to further increase the accuracy of the classification to 97%. 

## Code Examples
Show examples of usage:

````

````

## Features
List of features ready and TODOs for future development

sr no	| model	| train_r2_score	| test_r2_score
--- | --- | --- | ---|
0	| Linear Regressor	| 0.902539	| 0.899354
1	| KNN Regressor	| 0.935276	| 0.904540
2	| Random Forest Regressor	| 0.997856	| 0.984413
3	| SVM Linear	| 0.897939	| 0.896891
4	| SVM RBF	| 0.992589	| 0.986182
5	| Multi Output DT Bagging	| 0.875499	| 0.880045
6	| Adaboost_DecisionTree	| 0.999908	| 0.983499
7	| KNN Adaboost	| 0.972943	| 0.929250
8	| Adaboost_LinearSVM	| 0.896437	| 0.893522
9	| Gradient Boosting Regressor	| 0.999541	| 0.996787




* Awesome feature 1
* Awesome feature 2
* Awesome feature 3

## Status
Project is: _finished_


## Contact
Created by me and my teammate [Siddharth Oza](https://github.com/siddharthoza).

Feel free to contact me! My other projects can be found [here](http://www.gupta-harsh.com/projects/).


## Goal: 



## Data Set Information:
We perform energy analysis using 12 different building shapes simulated in Ecotect. 
The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. 
We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. 
The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.

## Attribute Information:
The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each of the two responses. 



