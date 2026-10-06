💳 Credit Risk Predictor using Logistic Regression

A machine learning project that predicts whether a customer has Good Credit or Bad Credit using Logistic Regression.

🎯 Project Objective

The goal of this project is to build a binary classification model that can predict customer credit risk based on financial, personal, employment, and credit-history information.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Google Colab
Jupyter Notebook
📊 Dataset

The dataset contains 1,000 customer records and 21 columns, including features such as:

Credit status
Credit history
Loan duration
Loan amount
Savings
Employment duration
Age
Housing
Job
Number of existing credits
Telephone
Foreign worker

Target: credit_risk

0 → Bad Credit
1 → Good Credit
🔄 Machine Learning Workflow
Dataset
   ↓
Data Cleaning & Inspection
   ↓
Exploratory Analysis
   ↓
Categorical/Numerical Feature Identification
   ↓
One-Hot Encoding
   ↓
Train-Test Split (80:20)
   ↓
Logistic Regression
   ↓
Prediction
   ↓
Model Evaluation
🤖 Model

Logistic Regression is used because this is a binary classification problem.

Categorical features are converted into numerical form using One-Hot Encoding, while numerical features are passed directly to the model.

📈 Model Evaluation

The model is evaluated using:

Accuracy Score
Confusion Matrix
Classification Report
True Positive (TP)
True Negative (TN)
False Positive (FP)
False Negative (FN)

The confusion matrix helps understand not only how many predictions were correct, but also what type of prediction errors the model made.

💡 Key Learning Outcomes

Through this project, I learned how to:

Perform basic data analysis using Pandas
Identify categorical and numerical features
Apply One-Hot Encoding
Split data into training and testing sets
Build a Logistic Regression classification model
Generate predictions
Evaluate classification performance using accuracy, confusion matrix, and classification report
🚀 Future Improvements
Compare Logistic Regression with other classification algorithms
Perform feature scaling and feature selection
Tune model hyperparameters
Compare multiple evaluation metrics
Deploy the model as a simple web application
