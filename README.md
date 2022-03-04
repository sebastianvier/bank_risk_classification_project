# bank_risk_classification_project

#### 1) Introduction

The aim of this project is to understand the behavior of a group of customers and predict, based on simple data which customers might or not accept a new credit card.

The data introduced has a total of columns, where one is the target is offer_accepted, and there are 5 continues variables, 4 discrete variables and 5 categorical variables. Furthermore there are around 18 000 total entries.

This is in its essence a binary classification; where the values in the target variable can be or 'Yes' (if the customer accepted the offer). Or 'No', when the he/she refuse it. As an important fact to tell on the get got, the distribution of the target values is not balanced. The ratio is about 16/1 or about 95/5. This is kind of expected as most people might refuse a credit card when asked.

In order to make the classification more valuable, a train test split was made before an exploratory analysis of the data. This was made to simulate that there is some data from where the model was created and then other different data was received. The performance of the data is calculated in this 'new data' received.

#### 2) Exploratory Analysis

The exploratory analysis was conducted in 3 steps. 