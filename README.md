# Capstone-Project-2 Project Summary :-

# Company's Introduction

Dirk Rossmann GmbH, commonly referred to as Rossmann, is one of the largest drug store chains in Europe with around 56,200 employees and more than 4000 stores.
The company was founded in 1972 by Dirk Rossmann with its headquarters in Burgwedel near Hanover in Germany. The Rossmann family owns 60% of the company. The Hong Kong-based A.S. Watson Group owns 40%, which was taken over from the Dutch Kruidvat in 2004.
The company logo consists of a red name and the symbol of a centaur integrated in the letter O: a mythical creature made of horse and man from Greek mythology, which symbolically stands for "Rossmann" (In English: "Horse man").

# Problem Overview
Rossman Sales Prediction data is a data set containing historical sales data for a retail chain. The data includes store information, such as competitor details, store type, holidays and sales transaction.
Using the data given we had to build a model for forecasting the sales in future.
To build a machine learning model, we first perform EDA with various plots for better visualization.
And then we split it into a training set and a test set and applied various machine learning algorithms using the training data to train the model. Finally, we evaluated the model's performance on the test data to see how well it predicted sales.

# Analysis Performed

Steps involved in building a ML Model:

Step 1: Data gathering and Understanding

Step 2: Data preparation

Step 3: Data Cleaning

Step 4: Exploratory data analysis

Step 5: Feature engineering and selection

Step 6: ML Model assumption and checks

Step 7: Data preparation for modelling

Step 8: Model Building

Step 9: Model Validation & Evaluation

Step 10: Predictions & Saving model using pickel library.

# Libraries used in EDA & Machine Learning:

Pandas
Numpy
Matplotib
Seaborn
Plotly
Sklearn
Scipy

# Graphs used for representation:

Bar plot
Pie plot
Box Plot
Grouped bar plot
Donut plot
Heatmap
Pair plot

# ML Models used for training & testing:

Linear Regression
Lasso Regression
Ridge Regression
Decision Tree Regressor
Extra Tree Regressor
XG Boost Regressor
Light GBM Regressor


# Insights from EDA impacting business:

The most selling and crowded store type is A.
More stores are opened during School holidays than State holidays.
Mondays have most sales since most of the Sundays are closed.
Promo 1 has given positive yields where as Promo 2 is a disaster.
Store type b has higher sales and customers per store than other store types.
Assortment b is available only at store type b and it has more sales and customers than any other assortment.

# Suggestions provided to increase the Sales:

There are very few B type stores, few more can be opened as average sales are quite high as compared to other types.
Assortment B is only available with store type B which can be extended to other types as well to cater the demands of customers.
Promo 2 should be discontinued and Promo 1 can be extended futher as it shows better results.
Very few stores are opened during State Holidays, so it suggested to open a subsequent amount of stores to serve in emergency purposes.

# ML Model selected for deployment: XG Boost

XGBoost is an efficient and easy to use algorithm which delivers high performance and accuracy as compared to other algorithms. XGBoost is also known as regularized version of GBM.

# Advantages:

High Accuracy: XGBoost Regressor is known for its high accuracy and performance compared to other machine learning algorithms.

Regularization: XGBoost has in-built L1 (Lasso Regression) and L2 (Ridge Regression) regularization which prevents the model from overfitting.

Parallel Processing: XGBoost utilizes the power of parallel processing and that is why it is much faster than GBM. It uses multiple CPU cores to execute the model.

Handling Missing Values: XGBoost has an in-built capability to handle missing values.

Cross Validation: XGBoost allows user to run a cross-validation at each iteration of the boosting process and thus it is easy to get the exact optimum number of boosting iterations in a single run.

# Limitations:

Complexity: XGBoost Regressor has a lot of hyperparameters to tune, which can make it difficult to optimize the model for a specific problem.

Overfitting: If not tuned properly, XGBoost Regressor can overfit the training data, which can lead to poor generalization on the test data.

Training time: Training time is pretty high for larger dataset, if compared against lightgbm.

# Suggestion:

When we are dealing with huge dataset & time is a constraint, also accuracy can be compromised a bit then we can prefer opting to Light GBM Model.
