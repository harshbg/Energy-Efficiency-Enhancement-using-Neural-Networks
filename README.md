# Project Name
> This study looked into assessing the heating load and cooling load requirements of buildings (that is, energy efficiency) as a function of building parameters.
The project was done as part of Machine Learning class at the University of Texas at Dallas.

The entire summary of the project can be found in the [Jupyter Notebook](https://github.com/harshbg/Energy-Efficiency-Enhancement-using-Neural-Networks/blob/master/Energy%20Efficiency%20Analysis%20.ipynb)

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies and Tools](#technologies-and-tools)
* [Setup](#setup)
* [Process](#process)
* [Code Examples](#code-examples)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
Add more general information about project. What the purpose of the project is? Motivation?

## Screenshots
![Example screenshot](./img/screenshot.png)

## Technologies and Tools
* Python 3.5
* TensorFlow

## Setup

The dataset used and its metadata can be found in the [dataset](). 
The jupyter notebook can be downloaded [here](https://github.com/harshbg/Energy-Efficiency-Enhancement-using-Neural-Networks/blob/master/Energy%20Efficiency%20Analysis%20.ipynb) and can be used to reproduce the result. 
Installation of TensorFlow would be required to run all the models. 
You can find the instructions to install TensorFlow in [installation guide](https://www.tensorflow.org/install/pip).

## Process

## Code Examples
Show examples of usage:

````

````

## Features
List of features ready and TODOs for future development
* Awesome feature 1
* Awesome feature 2
* Awesome feature 3

## Status
Project is: _finished_


## Contact
Created by me and my teammate [Siddharth Oza](https://github.com/siddharthoza).

Feel free to contact me! My other projects can be found [here](http://www.gupta-harsh.com/projects/).


## Goal: 
Adding cooling load and heating load can define the overall load of the apartment. Studied the trend of overall load and divided it into three classes, low efficient, high efficient and average efficient. 
Then train a deep learning model to predict the label. First I applied multioutput machine learning regressor models like KNN, logistic regression, random forest, decision tree, linear & kernalised SVM. 
After that I created a neural network classification model to increase the accuracy of the classification to 97%

## Source:
The dataset was created by Angeliki Xifara and was processed by Athanasios Tsanas, Oxford Centre for Industrial and Applied Mathematics, University of Oxford, UK).

## Data Set Information:
We perform energy analysis using 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.

## Attribute Information:
The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each of the two responses. 



