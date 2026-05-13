# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
COMPANY:CODTECH IT SOLUTIONS
NAME:RUPALI BORADE
INTERN ID:CTIS3470
DOMAIN:DATA ANALYTICS
DURATION:16 WEEKS
MENTOR:NEELA SANTOSH

#DESCRIPTION
Predictive Analysis Using Machine Learning

This project focuses on predictive analysis using machine learning techniques. The objective of the task is to build a machine learning model capable of predicting outcomes from a given dataset. For this project, the Titanic dataset was used to predict whether a passenger survived or not based on different features such as passenger class, gender, age, and fare.

The project was implemented using Python and popular data science libraries including Pandas, NumPy, Matplotlib, and Scikit-learn. Initially, the dataset was loaded using Pandas. Basic data exploration was performed to understand the structure and contents of the dataset.

During the preprocessing stage, only important features relevant to prediction were selected. These features included “Pclass”, “Sex”, “Age”, and “Fare”. Since machine learning algorithms work with numerical data, the “Sex” column was converted into numerical values using mapping, where male was represented as 0 and female as 1. Missing values in the dataset were handled by removing incomplete rows using the dropna() function.

Feature selection was an important step in this project. The selected features were assigned to the variable X, while the target variable “Survived” was assigned to y. The dataset was then divided into training and testing sets using the train_test_split() function from Scikit-learn. Eighty percent of the data was used for training the model, while twenty percent was reserved for testing and evaluation.

For model training, Logistic Regression was used because it is one of the most effective algorithms for binary classification problems. The model was trained using the training dataset with the fit() function. After training, predictions were generated on the test dataset using the predict() function.

The model performance was evaluated using accuracy score and classification report metrics. The accuracy score measured how correctly the model predicted survival outcomes, while the classification report provided detailed metrics such as precision, recall, and F1-score. These evaluation techniques helped in understanding the effectiveness of the machine learning model.

Overall, this project successfully demonstrated the complete workflow of predictive analysis using machine learning, including data preprocessing, feature selection, model training, prediction, and evaluation. The implementation shows how machine learning can be used to analyze historical data and predict future outcomes efficiently.

#OUTPUT
<img width="1219" height="307" alt="Image" src="https://github.com/user-attachments/assets/f506d672-7188-458d-be57-c3ec41cbde1e" />
<img width="965" height="229" alt="Image" src="https://github.com/user-attachments/assets/3479b9c4-b8c8-4b2a-8f5c-7c53405bb33e" />
<img width="1104" height="270" alt="Image" src="https://github.com/user-attachments/assets/1ee95a83-a336-4b2f-b1d9-d3b4d1dd3109" />
