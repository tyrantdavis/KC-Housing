# [KC-Housing Project](https://nbviewer.org/github/tyrantdavis/KC-Housing/blob/main/housing.ipynb)

Click the link above to see the project demo.

## Introduction
The goal of this project is to analyze housing data from King County, Washington, particularly around various attributes for the homes observed in the area and their prices.

This project will scope, analyze, prepare, plot data, and seek to explain the findings from the analysis.

Here are a couple of questions that this project has sought to answer:
- Which attribute has the greatest influence on price?
- What are some other attributes that have a strong influence on price?
- What patterns seem to exist regarding house prices and location?
- What is the maximum house price in the dataset?
- What are the features of the typical house in the dataset?

### Scenario
I am working on a machine learning tool that CapitalR Real Estate company will
use to predict an appropriate sale price for houses. I have proposed a model that will base the
price on various attributes such as the size of the home, the number of bathrooms and bedrooms,
location, and so forth.

**Data Sources:**

kc_house_data.csv


## Project Goals
In this project the perspective will be through a real estate analyst for CapitalR Real Estate. CapitalR Real Estate wants to readily and accurately predict housing prices. Therefore, the main objectives will be to comprehend characteristics about homes and their prices, what attributes contribute greatest to a home's price, and discover emergent trends regarding house prices and location. Some questions that are posed:

- Which attribute(s) has the greatest influence on price?
- What patterns seem to exist regarding house prices and location?



#### Why use a linear regression algorithm to produce a real estate price estimator?
A: The purpose of the model is to predict the price at which a house with particular attributes
will sell. This is a regression type of outcome. While other algorithms can also be used to
produce a regression outcome, linear regression is simple, relatively easy to implement, and
can produce a good result in many cases.

The house's price will be the output (the dependent variable). The model will determine (predict) the
price through multiple inputs (independent variables). This seems like an appropriate task for a
regression model.

## Data
An anonymized dataset that can be used to train the machine-learning model has been found. It is a CSV file containing more than 20,000 real estate transactions conducted in King County, Washington. 

## Conclusions

- Which attribute has the greatest influence on price?
    - sqft_living is the feature that has the greatest correlation to price 
- What are some other attributes that have a strong influence on price?
    - grade and sqft_above 
- What patterns seem to exist regarding house prices and location?
    - Expensive homes appear clustered around the lakes in Bellvue and Seattle, Lake Washington, and Lake Sammamish. Some expensive homes are not on the lake, however. Less expensive homes tend to be located in areas other than Bellvue and Seattle such as Federal Way, Auburn, Covington, Maple Valley, and Enumclaw - the southern sector of the county. 
- What is the maximum house price in the dataset?
    - The maximum price for a home in this dataset is $7,700,000 
- What are the features of the typical house in the dataset?
  
  The typical house:

    Does not have a "view" and is not on the waterfront.
    Has a grade of 7.
    Has a zipcode of 98103.
    Has 3 bedrooms, 2.5 bathrooms, and 1 floor level.

