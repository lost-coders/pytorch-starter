# Titanic Survival Analysis
## Overview
This is a Python project based on a dataset from a Kaggle competition, Titanic Machine Learning From Disaster. The goal of this repository is to get started with and to provide an analysis for those interested in data science or using machine learning on datasets with Python.

## Installation
To run this project:

1. Clone this repository from the terminal with `git clone https://github.com/lost-coders/titanic-analysis.git` or download it into a zip file by clicking:
[link](https://github.com/lost-coders/titanic-analysis/archive/master.zip)
2. Navigate to the directory where you cloned the repo or unzipped the repository.
3. Install the required dependencies with `pip install -r requirements.txt`.
4. Execute `jupyter notebook` from the terminal for an interactive view of the project.
5. Click on `Analysis.ipynb` on the Jupyter Notebook dashboard.

## Dependencies:
* [NumPy](http://www.numpy.org/)
* [Jupyter](http://jupyter.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [SciPy](http://www.scipy.org/)
* [Matplotlib](http://matplotlib.org/)
* [PyTorch](https://pytorch.org/)

## Titanic Machine Learning from Disaster Kaggle Competition
>The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.
>One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
>In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

Description from the competiton site [homepage](https://www.kaggle.com/c/titanic).

## Data Wrangling
* Import data with Pandas
* Cleanup data
* Explore data with visualizations using Matplotlib

## Data Analysis
* Supervised Machine learning techniques:
    + Logistic Regression Model
    + Basic Random Forest
    + Support Vector Machine (SVM)
    + Decision Tree
    + Plotting results

* Unsupervised Machine learning techniques:
    + K-means clustering
    + Plotting results

## Evaluation of the Analysis
* K-folds cross validation to assess results on local machine