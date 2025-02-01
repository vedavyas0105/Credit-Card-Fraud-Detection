# Credit-Card-Fraud-Detection
This repository features a credit card fraud detection project using logistic regression. It includes data preprocessing, exploratory analysis, and model training. The model's performance is assessed using the accuracy score to evaluate its effectiveness in identifying fraudulent transactions.

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning. A logistic regression model is trained and evaluated using accuracy scores to assess its effectiveness in identifying fraud.

## Dataset
The dataset contains anonymized credit card transactions, with features representing various attributes of each transaction. The target variable indicates whether a transaction is fraudulent or not.

## Features
- **Time**: Time elapsed since the first transaction in the dataset
- **V1 - V28**: Principal components obtained through PCA transformation
- **Amount**: Transaction amount
- **Class**: Target variable (0 for genuine, 1 for fraud)

## Project Workflow
1. **Importing Dependencies**
   - Load necessary Python libraries such as pandas, numpy, sklearn, and matplotlib.
2. **Loading Dataset**
   - Read the dataset into a pandas dataframe and explore its structure.
3. **Data Preprocessing**
   - Handle missing values (if any), normalize features, and split data into training and testing sets.
4. **Model Training**
   - Train a logistic regression model on the training dataset.
5. **Model Evaluation**
   - Use the accuracy score to evaluate model performance.
6. **Results & Analysis**
   - Interpret findings and discuss improvements.

## Requirements
To run this project, install the following dependencies:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage
Run the Jupyter Notebook to execute the entire workflow:
```bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

## Evaluation Metric
The model is evaluated using:
- **Accuracy Score**: Measures the proportion of correctly classified transactions.

## Future Improvements
- Experiment with different machine learning models.
- Use additional performance metrics like precision, recall, and AUC-ROC.
- Implement techniques to handle class imbalance (e.g., SMOTE, undersampling).

## License
This project is licensed under the MIT License.

