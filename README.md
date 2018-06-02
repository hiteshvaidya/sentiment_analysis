# Sentiment Analysis on mobile phone reviews

Sentiment Analysis by [Hitesh Vaidya](https://github.com/hiteshvaidya)

## Overview

This repository contains code for sentiment analysis on a dataset of mobile reviews. The dataset is downloaded from Kaggle. The code is developed entirely using [Scikit learn](http://scikit-learn.org/stable/index.html).
The code uses following algorithms: <br>
- Bag of Words
- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine
- Random Forest
- Decision Tree

## Dependencies

- python2.7
- virtualenv
- jupyter notebook
- pandas
- numpy
- nltk
- matplotlib
- sklearn
- beautifulsoup4
- re

## Data

Download the required data from this [kaggle](https://www.kaggle.com/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones/data) page.

## Installation

You may run this code in a virtual environment. I preferred to do so.<br>
Assuming that you have installed pip and virtualenv
Create a virtualenv and activate it. eg. let's call it `senti`
```
cd senti
git clone https://github.com/hiteshvaidya/sentiment_analysis.git
cd sentiment_analysis
pip -r install requirements.txt
```
In order to run jupyter notebook in a virtualenv, you need to create a new kernel. Follow this [blog](https://anbasile.github.io/programming/2017/06/25/jupyter-venv/) or this stackoverflow [page](https://stackoverflow.com/questions/37891550/jupyter-notebook-running-kernel-in-different-env) to create one.


## Usage

- Open jupter notebook. Now go in settings and change kernel to the new kernel that you just created.
- Now run the code in jupyter notebook.

## Acknowledgement

Credits for part of this code to [Suki Lau](https://github.com/sukilau).
