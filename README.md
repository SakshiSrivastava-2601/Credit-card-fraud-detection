# Credit-card-fraud-detection

# ABSTRACT


The annual losses from credit card theft amount to billions of dollars, making it a serious issue. Through the identification of patterns suggestive of fraudulent transactions, machine learning can be used to detect credit card fraud. When a credit card is physically lost or sensitive credit card data is lost, it is referred to as credit card fraud. There are numerous machine learning techniques available for detection. Creating a machine-learning model to identify credit card fraud is the goal of this research. A dataset of past credit card transactions will be used to train the model, and a holdout dataset of transactions that have not yet been seen will be used to assess it.

# Overview


The first of the two types of credit card theft is when an identity thief opens a credit card account in your name. From 48 to 2020, there were more reports of this fraudulent activity. The second kind occurs when an identity thief utilises an account you already have, typically by stealing the credit card details. From 2009 to 2020, there were more reports of this kind of fraud (Daly, 2021). We were prompted to address the problem analytically by employing various machine learning techniques to identify fraudulent credit card transactions within a large number of transactions after those figures drew our attention due to the sharp and quick increase in numbers over time.

# Data Source


The dataset was obtained from Kaggle.com, an open-source website. It includes information on two-day purchases performed by European credit card users in 2013. There are 284,808 rows and 31 characteristics in the dataset. The remaining three attributes are "Time," which contains the seconds that have passed between each attribute's first and subsequent transactions; "Amount," which is the amount of each transaction; and "Class," which contains binary variables where "1" denotes a fraudulent transaction and "0" does not. Twenty-eight attributes are numeric variables that have been transformed using PCA transformation due to the confidentiality and privacy of the customers.
Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

Coorelation Matrix

Two main Machine Learning Algorihtm are used:

Logistic Regresion

Random forest




