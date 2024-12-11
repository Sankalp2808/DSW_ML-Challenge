# Loan Status Prediction Challenge

This challenge involves predicting the loan status (approved or denied) using machine learning techniques. The goal is to explore the data, train models, and select the best model for prediction.

## Challenge Overview

This repository contains the following files to accomplish the challenge:

- **`eda.ipynb`**: Performs **Exploratory Data Analysis (EDA)** on the loan dataset. It includes data inspection, visualization, and insights into the features.
  
- **`model_.py`**: Defines the **model training pipeline**. It includes two machine learning models (Random Forest and Logistic Regression), with steps for data loading, preprocessing, training, testing, and prediction.

- **`model_selection.ipynb`**: Compares the performance of the models defined in `model_.py`. It performs model evaluation and selection based on metrics like accuracy and classification report.

**Run the Code**:
   - **EDA**: Open `eda.ipynb` and run all the cells to explore the dataset and visualize key insights.
   - **Model Training**: Run the `model_.py` script to train the models (Random Forest and Logistic Regression). The script will output evaluation metrics for each model.
   - **Model Selection**: Open `model_selection.ipynb` to compare the performance of the models and determine the best one based on cross-validation and evaluation results.

## Model Evaluation

The **Model Selection** notebook compares the Random Forest and Logistic Regression models based on evaluation metrics such as accuracy, precision, recall, and F1-score. It concludes by selecting the best model for deployment.

## Dataset

The challenge uses the following datasets:
- **`train_data.xlsx`**: Training data containing features and loan status (target).
- **`test_data.xlsx`**: Test data for making predictions.

## Conclusion

This challenge demonstrates how to:
- Conduct Exploratory Data Analysis (EDA) to understand the dataset.
- Train multiple machine learning models (Random Forest and Logistic Regression).
- Compare models and select the best-performing one based on evaluation metrics.

### Models Compared:
- **Random Forest**: A robust ensemble learning method that works well with complex and non-linear data.
- **Logistic Regression**: A simpler model that is easy to interpret and effective for linear relationships.

## Accuracy of Models:
- **Random Forest**: Achieved an accuracy of 76.19%.
- **Logistic Regression**: Achieved an accuracy of 75.12%.

## Best Model Selected:
Random Forest was selected as the best model due to its higher accuracy and better handling of complex, non-linear relationships in the dataset.
