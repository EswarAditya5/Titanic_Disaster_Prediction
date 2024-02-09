# Titanic_Disaster_Prediction

## Data Description:

Data collection Link:
Data [Click Here](https://www.kaggle.com/competitions/titanic)

### Overview
The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The training set should be used to build your machine-learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.


**Data Dictionary:**
|Variable|	Definition|	Key|
|:--:|:--:|:--:|
|survival|	Survival	|0 = No, 1 = Yes|
|pclass	|Ticket class|	1 = 1st, 2 = 2nd, 3 = 3rd|
|sex|	Sex	| male, female|
|Age|	Age in years	||
|sibsp	|# of siblings/spouses aboard the Titanic	||
|parch	|# of parents/children aboard the Titanic	||
|ticket	|Ticket number	||
|fare|	Passenger fare||	
|cabin|	Cabin number | A, B, C, D, E, F, G, T|
|embarked	|Port of Embarkation	|C = Cherbourg, Q = Queenstown, S = Southampton|

**Variable Notes:**<br>
**pclass:** A proxy for socio-economic status (SES)<br>
        1st = Upper.<br>
        2nd = Middle.<br>
        3rd = Lower.<br>
**age:** Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5<br>
**sibsp:** The dataset defines family relations in this way...<br>
**Sibling:** brother, sister, stepbrother, stepsister.<br>
**Spouse:** husband, wife (mistresses and fiancés were ignored)<br>
**parch:** The dataset defines family relations in this way...<br>
**Parent:** mother, father.<br>
**Child:** daughter, son, stepdaughter, stepson.<br>
    Some children traveled only with a nanny, therefore parch=0 for them.<br>


## Description:
- This is the legendary Titanic ML competition – the best, first challenge for diving into ML competitions and familiarizing yourself with how the Kaggle platform works.<br>
- If you want to talk with other users about this competition, join our Discord! We've got channels for competitions, job postings and career discussions, resources, and socializing with your fellow data scientists.<br> 
        Follow the link here: [Discord](https://discord.gg/kaggle).<br>
- The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.<br>

## The Challenge:
- The sinking of the Titanic is one of the most infamous shipwrecks in history.<br>
- On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.<br>
- While there was some element of luck involved in surviving, some groups of people were more likely to survive than others.<br>
- In this challenge, we ask you to build a predictive model that answers the question: “What sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).<br>

## What Data Will I Use in This Competition?
- In this competition, you’ll gain access to two similar datasets that include passenger information like name, age, gender, socio-economic class, etc. One dataset is titled train.csv and the other is titled test.csv.<br>
- Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.<br>
- The test.csv dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.<br>
- Using the patterns you find in the train.csv data, predict whether the other 418 passengers on board (found in test.csv) survived.<br>

## Goal
Predict if a passenger survived the sinking of the Titanic or not.<br>
For each in the test set, we need to predict either 0 or 1 value for the target variable.
