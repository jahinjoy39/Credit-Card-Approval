# 💳 Credit Card Approval Default Prediction

This project uses a machine learning model to predict whether a credit card holder will default on their payment. It uses a Decision Tree Classifier to make predictions based on various financial and demographic attributes.

## 📁 Files

- `Credit_Card.ipynb` — Jupyter Notebook containing all code for data processing, model training, and evaluation.
- `cc_approvals.data` — Dataset file (make sure to include it in your repo if used).

## 📊 Dataset Overview

The dataset includes features such as:

- `LIMIT_BAL`: Credit limit
- `SEX`, `EDUCATION`, `MARRIAGE`: Demographic info
- `AGE`: Age of the cardholder
- `PAY_0`, `PAY_2`, ...: Payment history
- `BILL_AMT1`, `PAY_AMT1`, etc.: Bill and payment amounts
- `default.payment.next.month`: Target variable (1 = default, 0 = no default)

## 🧠 Model Info

- **Model**: Decision Tree Classifier
- **Libraries Used**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

The notebook includes:

- Data cleaning and preprocessing
- Feature selection
- Model training
- Evaluation metrics (accuracy, confusion matrix)
- Visualization of decision tree (optional)

## 🚀 Getting Started

### Prerequisites

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
