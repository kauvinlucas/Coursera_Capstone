# Coursera_Capstone
### Capstone Project for the IBM Data Science Professional Certificate
  
  Start date: Sep 05, 2020
  
  End date: Sep 21, 2020

*Note: this is a work in progress*

## Introduction
Car road accidents are the number one problem in US road transportation, accounting for 99% of transportation injuries and representing an economic cost of 150 billion USD annually [1]. Deaths and injuries from the accidents are some of the issues concerned by insurance companies, healthcare institution and governments. It’s very important for them to be able to predict the severity rate of an accident given some known variables. This project will attempt to employ classification models to predict severity rates and compare the accuracy of each built model.

## Business problem
Predicting car accidents severity is one of the biggest challenges faced by many actors. No single factor can help in explaining the severity of an accident, and the relationship between these factors, although intuitively positive, are mostly unclear from a statistical point of view. But while each accident may be unique, accumulating insights from each accident may show macro trends and thus allow us to make accurate predictions, which might aid the actors in their decision-making processes. Taking these several seemly uncorrelated variables into a single accurate prediction model is a long process that requires finding generalizable predictive patterns. That can only be achieved by using machine learning algorithms.

## Description of the data
The used data was produced by the Seattle government. It describes the accidents occurred between 2004 and 2020 in the city, along with severity codes. The severity codes are labeled as numbers between 0 and 3, from least to most severe. The data had 37 features. Before the Feature Selection stage, two more features were added: “INCHOUR” and “ISHOLIDAY”. The selected features were the following:
| Feature name       | Description     | Comments     |
| :------------- | :----------: | -----------: |
| SEVERITYCODE | A code that corresponds to the severity of the collision:    | This will be the output variable   |
| ADDRTYPE| A description of the collision address type | It may affect collision severity |
| INATTENTIONIND| Whether the person was not paying attention | It may affect collision severity |
| UNDERINFL| Whether the person was driving under the influence of alcohol | It may affect collision severity |
| WEATHER| A description of the weather conditions during the time of the collision | It may affect collision severity |
| ROADCOND| The condition of the road during the collision | It may affect collision severity |
| LIGHTCOND| The light conditions during the collision| It may affect collision severity |
| SPEEDING| Whether or not speeding was a factor in the collision| It may affect collision severity |
| INCHOUR| Hour of the day when the collision has occurred | Newly created dimension. It may affect collision severity |
| ISHOLIDAY| Whether or not collision has occurred in holiday | Newly created dimension. It may affect collision severity |

The data was described by using maps and histograms. Pre-processing of the data included transformation by Feature Selection, enconding by using one hot encoding and binary encoding, Feature Reduction and Normalization.

The following classification algorithms were employed to predict and evaluate the data:
1.	K Nearest Neighbours (KNN)
2.	Decision Tree
3.	Logistic Regression
4.	Random Forest
5.	Support Vector Machine (SVM)

To be continued.
