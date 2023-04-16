# Customer Loan Prediction
This project aims to predict whether a customer will default on a loan based on their credit history and other factors.

## Dataset
The project uses two datasets train.csv and test.csv. The train dataset contains 614 customer records, with features such as loan amount, credit score, and employment status. The test dataset contains 367 customer records, with the same features but without the target variable (whether the customer defaulted or not).

## Algorithm
We developed a machine learning algorithm to predict loan defaults based on the train dataset. We used the Python programming language and the scikit-learn library to implement the algorithm. The algorithm uses logistic regression to classify customers into two categories: defaulted or not defaulted. We trained the algorithm on the train dataset and evaluated its performance using cross-validation.

## Predictions
We used the trained algorithm to make predictions on the test dataset. We created a new file called test_final.csv, which contains the predicted target variable for each customer record in the test dataset.

## Analysis
We analyzed the train dataset using various visualizations to gain insights into the data. We used Python libraries such as Pandas, Matplotlib, and Seaborn to plot graphs of the distribution of loan amount, credit score, employment status, and other features.
