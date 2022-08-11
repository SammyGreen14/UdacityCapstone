# UdacityCapstone
Written by Sammy Green


## Motivation
This project investigates the use of ML models in classifying names by nationality and gender.  
The code in this repository is used to fill in the blog post on medium which can be found at https://medium.com/@samantha.green/names-linking-to-nationality-and-gender-c7cc7c4a3bcc

### Questions Asked
Can a model predict a person's nationality accurately given only a first name?

Can a model predict a person's gender accurately given only a first name?

## Data
Kaggle data set with 4,695 names along with gender and nationality.  
https://www.kaggle.com/datasets/hemendrasr/name-by-nationality?resource=download

## Installation 
Packages used include pandas, matplotlib, sklearn, and numpy

## Files
Nationality.ipynb: Jupyter Notebook containing data analysis
names-by-nationality.csv: CSV file of data set

## Resolution
While models were able to predict the nationality with about a 50% accuracy and the gender with about a 60% accuracy, k-nearest neighbors seemed to mostly just return the most common classes. Japanese names were the exception to this with accuracy above 75%. 
