# Starbucks data analysis capstone project
## Overview
My objective in this project is to find trends and relations between users information and offer data based on generated output data from starbocks mobile app. Also I will create a Machine Learning model for predict response of a customer to the offer. 
Please check out the article that I wrote in [Medium Article](https://vajed001.medium.com/data-analyzing-for-starbucks-app-97ae8bb8a24f). 


# Table of contents
1. [Getting Started](#par1)
3. [Project Summary](#summary)
3. [Datasets](#datasets)
4. [License](#License)
5. [Contact](#Contact)

## Getting Started <a name="par1"></a>

This project uses the following libraries:
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [sklearn](https://scikit-learn.org/stable/)
* [python](https://www.python.org/download/releases/3.0/)


In order to get a local copy of the project, you will need to download the dataset from the data folder, and add it to the same folder of the project.   
The project has the following:
- Starbucks_Project.ipynb
- data folder

The jupyter notebook contains all code and data analysis.

Download the [jupyter](https://jupyter.org/) notebook from this repository and have fun!

## Project Summary <a name="summary"></a>
In this project, I will be analyzing given dataset and try to find patern and relation between users demographic and offer data. Also, I will build a machine learning model to predict whether a customer will complete an offer or not. 

Each customer on  has an account that can include demographic information on the user. A user can make a purchase, receive an offer, view an offer or complete an offer(Event column).
There are three types of offers that can be sent: buy one get one free(BOGO), discount, and informational.
* BOGO: a user needs to spend a certain amount to get a reward equal to that threshold amount.
* Discount: a user gains a reward equal to a fraction of the amount spent.
* Informational: more advertisement for a drink but not includes any kind discount. 

**Problem Statement:**   
The problem is predict customer behaviour in term of predicting how does a customer respond or complete an offer when  offer sent to them.

## Dataset <a name="datasets"></a>

1.Datasets:
There are three datasets available:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

2. Coding could be available in the Jupytr notebook.
