1. SKLEARN.MODEL\_SELECTION

from sklearn.model\_selection import train\_test\_split

First of all, the sklearn.model\_selection is a module that provides functions for splitting into training and test sets, evaluating machine learning models, and performing validation

In any machine learning model datasets, we divide them into 2 types of data, one is only for testing and one is only for training with the normally 80/20 ratio.

The 80/training data will be used to train the model and the 20/test data will be used to test the model, which will use certain mathematical functions to assess the accuracy of the model.

Way to execute this:  
x\_train, x\_test, y\_train, y\_test \= train\_test\_split(x, y, test\_size=0.3, random\_state=42)

2. SKLEARN.PREPROCESSING

from sklearn.preprocessing import PolynomialFeatures, StandardScaler, StandardScaler, MinMaxScaler, LabelEncoder, OneHotEncoder, Inputer

The sklearn.preprocessing model is a module that provides certain methods to alter the value of the whole datasets. This module offers a wide array of tools for data processing, which explains preprocessing—modules to process after training and testing. 

These methods include techniques for scaling, encoding, transforming, and inputting data. 

For Linear Regression