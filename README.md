# diabetes-prediction-model-comparison 
**Project Description**
This project is a Machine Learning-based Diabetes Prediction System. It uses patient medical data to predict whether a person has diabetes or not. Multiple machine learning models are trained and compared to find the best performing model.
**Technologies Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
**Dataset**
Dataset used: diabetes.csv
It contains medical features such as:
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Age
**Target variable:**
Outcome (0 = No Diabetes, 1 = Diabetes)
**Project Workflow**
1. Data Loading
The dataset is loaded using Pandas.
2. Data Exploration
Checked:
Shape of dataset
Data types
First few rows
Summary statistics
Missing values (isnull)
3. Data Visualization
Correlation heatmap to understand relationships between features
Class distribution plot (Outcome)
Age distribution plot
4. Data Preprocessing
Separated features and target:
X = features
y = target
Split data into:
Training set (80%)
Testing set (20%)
Applied Standardization using StandardScaler
Mean = 0
Standard deviation = 1
5. Model Training
Three machine learning models were trained:
Support Vector Machine (SVM)
Logistic Regression
Random Forest Classifier
6. Model Evaluation
Models were evaluated using:
Accuracy Score
Confusion Matrix
Classification Report (Precision, Recall, F1-score)
7. Model Comparison
A comparison table is created:
Model	Accuracy
SVM	(0.785714)
Logistic Regression	(0.766234)
Random Forest	(0.720779)
**Results**
The models are compared to find the best performing algorithm for diabetes prediction.
Typically, SVM gives strong performance, but results may vary depending on data.
