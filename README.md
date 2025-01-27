# Heart-Disease-Prediction

Heart Disease Prediction using Logistic Regression

This project uses Logistic Regression to predict the likelihood of heart disease based on medical data. The model achieves an accuracy of 85% on training data and 82% on test data.

Table of Contents

Overview

Technologies Used

Setup Instructions

Data Processing

Model Training

Performance

Contact

Overview

Heart disease prediction is crucial for early diagnosis and treatment. This project utilizes a dataset of 303 samples with 14 features. Logistic Regression was chosen for its simplicity and interpretability.

Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

Setup Instructions

Clone this repository.

Install required dependencies:

pip install numpy pandas scikit-learn matplotlib seaborn

Add the dataset (heart_disease_data.csv) to the project directory.

Data Processing

Handled missing values and performed exploratory data analysis (EDA).

Scaled features using StandardScaler.

Split the data into training and test sets with an 80-20 ratio.

Model Training

The Logistic Regression model was trained and evaluated:

Training Accuracy: 85%

Test Accuracy: 82%

Performance

Confusion Matrix:

[[23  5]
 [ 6 27]]

Precision, Recall, F1-Score: Balanced metrics indicating a robust model.

ROC-AUC Score: 0.85

Contact

Author: Christy B MoncyEmail: christybmoncy1403@gmail.com

