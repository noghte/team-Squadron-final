# Team-Squadron-Final [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Team Members
Denish Khetan\
Mohammadreza Iman

See the [CONTRIBUTORS.md](https://github.com/dsp-uga/team-Squadron-final/blob/master/CONTRIBUTORS.md) file for details.

## Getting Started

Follow the below steps for installation and to run the training and testing sets.

## Prerequisites

- [Python 3.6](https://www.python.org/downloads/release/python-360/)
- [Rstudio](https://www.rstudio.com/)
- [Anaconda](https://www.anaconda.com/) - Python Environment virtualization.
- [Keras](https://keras.io/#installation) - Open-source neural network library
- [Tensorflow](https://www.tensorflow.org/) - API used as Backend for Keras

## Problem Statement

Based on the given customer transaction data by Santander Bank, identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. 

## Installation

### Anaconda 

Anaconda is a free and open-source distribution of the Python and R programming languages for scientific computing, that aims to simplify package management and deployment.

Download and install Anaconda from (https://www.anaconda.com/distribution/#download-section). 

### Keras 

Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. You can install keras using pip on command line ```sudo pip install keras```.

### Tensorflow 

You can install Tensorflow using pip on command line, for CPU ```sudo pip install tensorflow``` and for GPU ```sudo pip install tensorflow-gpu```

## Dataset

Anonymized dataset containing numeric feature variables, the binary target column (classification), and a string ID_code column. There is no deatils about the feature, just tabular data. No correlation between data, the highest correlation is 0.08. There are about 200 features. Very unbalanced training set with less than 15% having 1.\
**Training dataset:** 200,000 samples consist of 201 features and the target\
**Test dataset:** 200,000 instances consist of same 201 features of the training set

## Results 

|           Model           |Accuracy on Training dataset|Accuracy on Testing dataset|
|---------------------------|---------------------------|---------------------------|
|Regression|0.1799866|NA|
|Ridge regression|0.1799114|NA|
|LASSO regression|0.1799598|NA|
|Decision Tree|0.8396|0.5662|
|**Random Forest**|**0.7241**|**0.8050**|
|Support Vector Machine (Kernel:Sigmoid)|0.9005|0.5003|
|Support Vector Machine (Kernel:Poly)|0.9000|0.5000|
|Support Vector Machine (Kernel:Gaussian)|0.9101|0.5539|
|Sum-Product Network|0.6768|0.6753|
|Neural Network|0.7224|0.7253|

## Ethical Implications 
These models should only be used for study purpose, not to harm or take advantage of anything in any manner.

## Acknowledgments
- This project was completed as a part of the Data Science Practicum 2019 course at the University of Georgia. This work would not have been possible without the support of Dr. Shannon Quinn, [Assistant Professor, University of Georgia Departments of Computer Science] who worked actively to provide us with academic time and advice to pursue those goals.
- Other resources used have been cited in their corresponding wiki page.

### References
- https://www.rstudio.com/
- For wiki page of Decision Tree we used the information provided on page https://www.geeksforgeeks.org/decision-tree/ 
- For the wiki page of Random Forest Tree we used information provided on page https://towardsdatascience.com/the-random-forest-algorithm-d457d499ffcd
- For the Support Vector MAchine page we took infromation from page https://towardsdatascience.com/the-random-forest-algorithm-d457d499ffcd
- For sum-product model theory we used page https://spn.cs.washington.edu/
- For the Neural Network theroy we referred to page https://github.com/dsp-uga/team-Squadron-final/wiki/6.-Neural-Network
