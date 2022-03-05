# bank_risk_classification_project

#### 1) Introduction

The aim of this project is to understand the behavior of a group of customers and predict, based on simple data which customers might or not accept a new credit card.

The data introduced has a total of columns, where one is the target is offer_accepted, and there are 5 continues variables, 4 discrete variables and 5 categorical variables. Furthermore there are around 18 000 total entries.

This is in its essence a binary classification; where the values in the target variable can be or 'Yes' (if the customer accepted the offer). Or 'No', when the he/she refuse it. As an important fact to tell on the get got, the distribution of the target values is not balanced. The ratio is about 16/1 or about 95/5. This is kind of expected as most people might refuse a credit card when asked.

In order to make the classification more valuable, a train test split was made before an exploratory analysis of the data. This was made to simulate that there is some data from where the model was created and then other different data was received. The performance of the data is calculated in this 'new data' received.

#### 2) Exploratory Analysis

The exploratory analysis was conducted in 4 steps. First the target data was explore, and the result where as mentioned before a lack of balance between the two variables in the target.

Then an analysis was made on the continues data was conducted. Showing the distribution of the data. Since the data used was distributed in 4 continues period, an analysis on the evolution of the values was also conducted.

Third an an analysis of the discrete and finally an analysis on the categorical variables. Since the target was binary, the way the discrete and categorical variables was by the creation of charts that show the distribution of the yes on no, per type of value in each variable. Then based on the split of the target a percentage variance was calculated. Because of the importance of the offers that where accepted in this excercise; the variance of this percentage for the 'yes' value was the most considered.

This analysis is not exhaustive and could be improved by understanding the relationship between columns and also between different d-types. For this first approach and first model; it was thought that this was enough.

#### 3) First models and the problems of imbalance

#### 4) Trying on different sets of non-continues variables

#### 5) Adding continues variables to the mix.