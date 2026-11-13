## Rainfall Prediction using Machine Learning - Python

Today there are no certain methods by using which we can predict whether there will be rainfall today or not. Even the meteorological department's prediction fails sometimes. In this article, we will learn how to build a machine-learning model which can predict whether there will be rainfall today or not based on some atmospheric factors. This problem is related to Rainfall Prediction using Machine Learning because machine learning models tend to perform better on the previously known task which needed highly skilled individuals to do so.

#### Importing Libraries and Dataset

**Python** libraries make it easy for us to handle the data and perform typical and complex tasks with a single line of code.

1.**Pandas** - This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.
2. **Numpy** - Numpy arrays are very fast and can perform large computations in a very short time.
3. **Matplotlib/Seaborn** - This library is used to draw visualizations.
4. **Sklearn** - This module contains multiple libraries are having pre-implemented functions to perform tasks from data preprocessing to model development and evaluation.
5. **XGBoost** - This contains the eXtreme Gradient Boosting machine learning algorithm which is one of the algorithms which helps us to achieve high accuracy on predictions.
6. **Imblearn** - This module contains a function that can be used for handling problems related to data imbalance

#### Data Cleaning

The data which is obtained from the primary sources is termed the raw data and required a lot of preprocessing before we can derive any conclusions from it or do some modeling on it. Those preprocessing steps are known as **data cleaning** and it includes, outliers removal, null value imputation, and removing discrepancies of any sort in the data inputs.

#### Exploratory Data Analysis

**EDA** is an approach to analyzing the data using visual techniques. It is used to discover trends, and patterns, or to check assumptions with the help of statistical summaries and graphical representations. Here we will see how to check the **data imbalance and skewness** of the data.

#### Model Training

We will separate the features and target variables and split them into training and testing data by using which we will select the model which is performing best on the validation data. Train the models for classification and train them on our training data.

-LogisticRegression
-XGBClassifier
-SVC

#### Model Evaluation

From the above accuracies, we can say that Logistic Regression and support vector classifier are satisfactory as the gap between the training and the validation accuracy is low. Let's plot the **confusion matrix** as well for the validation data using the SVC model.

































