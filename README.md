# Breast Cancer Prediction

Machine learning project to predict whether a breast tumor is malignant or benign using Logistic Regression.

## Dataset
Wisconsin Breast Cancer dataset (569 patients, 30 features), available in scikit-learn.

## Approach
1. Loaded the dataset
2. Split into 80% training and 20% testing data
3. Scaled features using StandardScaler
4. Trained a Logistic Regression model
5. Evaluated on unseen test data

## Results
- Accuracy: 97.37%
- Confusion matrix: 41 malignant and 70 benign cases predicted correctly, only 3 out of 114 misclassified

## Tools
Python, scikit-learn, Jupyter Notebook / Google Colab

## How to run
Open `cancer_prediction.ipynb` in Google Colab and click Runtime > Run all.
