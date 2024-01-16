# Predicting-Credit-Card-Approvals

## Overview

This Python script aims to predict credit card approval status using a logistic regression model. The dataset includes various features related to credit card applications. The script follows a structured pipeline, including data loading, preprocessing, model training, and evaluation.

## Code Structure

### 1. Data Loading and Exploration

- **Pandas:** Used to load the dataset and perform initial exploratory data analysis.

### 2. Data Preprocessing

- **Handling Missing Values:** Identifies and imputes missing values using mean imputation and the most frequent value for categorical columns.
- **Categorical Feature Encoding:** Converts categorical features into numerical using one-hot encoding.

### 3. Model Training

- **MinMax Scaling:** Scales features to a specified range using MinMaxScaler.
- **Logistic Regression:** Utilizes the logistic regression algorithm for binary classification.

### 4. Model Evaluation

- **Confusion Matrix:** Assesses model performance using the confusion matrix.
- **Grid Search:** Conducts grid search for hyperparameter tuning.

## How to Use

1. Ensure you have Python installed on your machine.
2. Clone the repository: `git clone https://github.com/your-username/credit-card-approval.git`
3. Navigate to the project directory: `cd credit-card-approval`
4. Install dependencies: `pip install -r requirements.txt`
5. Run the script: `python credit_card_approval.py`

## Results

- Achieves 100% accuracy on the test set after preprocessing and logistic regression.
- Utilizes GridSearchCV for hyperparameter tuning to enhance model performance.

## 🚀 Key Achievements

- Efficiently handles missing values and categorical features.
- Implements a logistic regression model for credit card approval prediction.
- Utilizes grid search for optimal hyperparameter tuning.

## 📊 Model Evaluation

- Accuracy: 100%
- Confusion Matrix:
  ```
  [[103, 0],
   [0, 125]]
  ```

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn

Feel free to explore, contribute, and provide feedback! 🌟
