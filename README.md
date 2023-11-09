# CreditCardFraudDetection

## Steps in a Machine Learning Project

1. **Understanding the Problem Statement:**
   - Clearly define the problem you are trying to solve and understand the requirements.

2. **Data Collection:**
   - Gather relevant data for your project. Ensure the data is comprehensive and representative.

3. **Exploratory Data Analysis:**
   - Explore the dataset to gain insights into its structure, patterns, and potential challenges.

4. **Data Pre-Processing:**
   - Clean and prepare the data for modeling. Handle missing values, outliers, and encode categorical variables.

5. **Model Training:**
   - Choose an appropriate machine learning model and train it on your pre-processed data.

6. **Model Evaluation:**
   - Assess the performance of your model using appropriate metrics. Fine-tune the model if necessary.

## Credit Card Default Prediction

### Project Overview

1. **Objective:**
   - Predict the probability of credit card default based on credit card owner's characteristics and payment history.

2. **Dataset:**
   - [Credit Card Default Dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)
   - 30,000 records, 25 columns

### Data Description

- **ID:** Client ID
- **LIMIT_BAL:** Amount of given credit (NT dollars)
- **SEX:** Gender (1=male, 2=female)
- **EDUCATION:** Education level
- **MARRIAGE:** Marital status
- **AGE:** Age in years
- **PAY_0 to PAY_6:** Repayment status
- **BILL_AMT1 to BILL_AMT6:** Amount of bill statement
- **PAY_AMT1 to PAY_AMT6:** Amount of previous payment
- **default.payment.next.month:** Default payment (1=yes, 0=no)

### Project Requirements

#### Virtual Environment Setup:


conda create -p venv python==3.8 -y
conda activate venv

# Library Installation:

pip install -r requirements.txt

- ## Best Model

The best model found for Credit Card Default Prediction is RandomForestClassifier with an accuracy score of 0.8126.

- ### Contributors:

Mohammad Aadil
