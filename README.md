# Loan Default Prediction in P2P Lending

## Project Overview

The goal of this project is to predict loan defaults in **Peer-to-Peer (P2P) lending platforms** using **machine learning models**. The project applies various predictive techniques to analyze borrower data and predict whether a borrower is likely to default on their loan.

### Key Objectives:
- **Predict loan defaults**: The primary aim is to predict which borrowers are likely to default based on their personal financial information.
- **Data analysis**: Identify patterns and key features that influence loan defaults.
- **Model evaluation**: Use machine learning algorithms like **Logistic Regression**, **Random Forest**, and **Neural Networks** to build predictive models.
- **Risk Analysis**: Assess the potential risk for lenders based on borrower data.

## Data Sets Used:

This project uses the following datasets:

### 1. **trainData.csv**: Training data for model development
- **Number of Samples**: **X rows** (observations)
- **Number of Features**: **Y columns** (variables such as borrower income, loan amount, credit score, etc.)
- **Description**: This dataset contains historical data of borrowers. It includes features like:
  - **Income**: Borrower's income level.
  - **Loan Amount**: Amount of the loan taken by the borrower.
  - **Loan Term**: Duration of the loan.
  - **Credit Score**: Borrower's credit score.
  - **Loan Default Status**: The target variable indicating whether the borrower defaulted (1) or not (0).
  
This dataset is used to **train** the machine learning models.

### 2. **testData.csv**: Test data to evaluate model performance
- **Number of Samples**: **X rows** (observations)
- **Number of Features**: **Y columns** (same features as `trainData.csv`)
- **Description**: This dataset is used to test the model's predictions on new, unseen data. It includes the same features as `trainData.csv` but does not contain the target variable for loan default status, allowing the model's predictions to be evaluated.
  
This dataset is used to **evaluate** model performance and ensure generalization to unseen data.

### 3. **varDescription.csv**: Variable descriptions
- **Number of Rows**: **Z rows** (each row corresponds to a feature in the datasets)
- **Description**: This file provides descriptions of each feature/column in the `trainData.csv` and `testData.csv` datasets. It explains what each feature represents, e.g., loan amount, credit score, etc.

This file helps in understanding the meaning behind the variables used in the model.

## How to Use:

### Prerequisites:
Make sure you have **Python** installed along with the required libraries. You can install the dependencies with:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Loan-Default-Prediction.git
