# Loan Status Prediction Using Machine Learning

## Overview
This project predicts loan approval status using machine learning models. It preprocesses loan applicant data, trains multiple classifiers, evaluates their performance using cross-validation, and provides a Tkinter-based GUI for user-friendly loan prediction.

## Features
- Data preprocessing (handling missing values, encoding categorical features, feature scaling)
- Model training using Logistic Regression, SVM, Decision Tree, Random Forest, and Gradient Boosting
- Model evaluation using cross-validation, confusion matrices, and accuracy scores
- Hyperparameter tuning with GridSearchCV and RandomizedSearchCV
- GUI for user-friendly loan status prediction

## Installation
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install pandas numpy scikit-learn matplotlib joblib tkinter
```

### Clone the Repository
```bash
git clone https://github.com/your-repo/loan-status-prediction.git
cd loan-status-prediction
```

## Usage
### 1. Run the Machine Learning Model
To train the model and evaluate classifiers, run:
```bash
python loan_prediction.py
```
This script will preprocess the dataset, train models, evaluate them, and save the best-performing model.

### 2. Run the GUI Application
To use the Tkinter-based GUI for loan status prediction, execute:
```bash
python loan_gui.py
```
Enter the required applicant details in the GUI, click **Predict**, and receive an approval status.

## Model Evaluation
- Cross-validation with different classifiers
- Confusion matrix visualization
- Hyperparameter tuning for improved accuracy

## Future Improvements
- Deploy as a web application using Flask or Django
- Enhance the feature engineering process
- Use deep learning models for better accuracy
- Integrate real-world financial datasets

## License
This project is licensed under the MIT License.

---
For contributions, pull requests, and further discussions, feel free to connect!
