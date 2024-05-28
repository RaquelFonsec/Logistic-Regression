# Logistic-Regression

Heart Disease Classification Analysis
Context
The dataset used in this analysis is the Statlog Heart Disease dataset obtained from the UCI repository. It contains data from 270 individuals with 14 columns (extracted from a larger set of 75). There are no missing values. The classification task is to predict whether an individual suffers from heart disease or not (0: absence, 1: presence).

This study is important because health is a vital research point to better assist patients with certain conditions. Additionally, high blood pressure often presents no symptoms, yet if left untreated, it can be a major contributor to more serious health conditions such as stroke or heart attack.

Data Dictionary
This dataset contains 13 attributes and one target variable. It includes 8 nominal values and 5 numerical values. The detailed description of all these features is as follows:

Age: age of patients in years
Sex: (Male: 1; Female: 0)
Chest Pain Type (cp): categorized into 4 categories:
0: typical angina
1: atypical angina
2: non-anginal pain
3: asymptomatic
Resting Blood Pressure (trestbps): patient's blood pressure level at rest in mm/HG
Cholesterol (chol): serum cholesterol in mg/dl
Fasting Blood Sugar (fbs): fasting blood sugar levels > 120 mg/dl represented as 1 for true and 0 for false (Nominal)
Resting Electrocardiographic Results (restecg): represented in 3 distinct values:
0: normal
1: with ST-T wave abnormality (T wave inversions and/or ST elevation or depression > 0.05 mV)
2: showing probable or definite left ventricular hypertrophy by Estes' Criteria
Maximum Heart Rate Achieved (thalach): maximum heart rate achieved
Exercise Induced Angina (exang):
0: No
1: Yes
ST Depression Induced by Exercise Relative to Rest (oldpeak)
Slope: ST segment measured in terms of slope during peak exercise
0: upsloping
1: flat
2: downsloping
Number of Major Vessels (ca): (0–3) (nominal)
Thalassemia (thal): a blood disorder called thalassemia
0: NULL
1: normal blood flow
2: fixed defect (no blood flow in some part of the heart)
3: reversible defect (blood flow is observed but not normal) (nominal)
Target: target variable to predict whether a patient has heart disease or not (1: yes, 0: no)
Questions:
Perform an exploratory data analysis observing the main variables and their relationship with the target.
Build a logistic regression model to classify whether the individual suffers from heart disease or not.
Analyze the result of logistic regression and plot the confusion matrix.
Exploratory Data Analysis:
During the exploratory data analysis, we observed that variables such as age, sex, chest pain type, resting blood pressure, cholesterol, and others have varied distributions. For example, the average age of patients is approximately 54 years, and most patients are male (approximately 68%). When analyzing the relationship with the target variable (target), we observed that some variables, such as resting blood pressure (trestbps) and serum cholesterol (chol), may show significant differences between patients with and without heart disease.

Logistic Regression Model:
We built a logistic regression model to predict whether an individual suffers from heart disease or not. We used all available variables as features to train the model.

Analysis of Logistic Regression Result and Confusion Matrix:
After training the logistic regression model, we evaluated its performance using metrics such as accuracy, precision, recall, and F1-Score. With an accuracy of approximately 92.59%, we can conclude that the model has good prediction capabilities. However, when analyzing the confusion matrix, we observed that the model had some false positives and false negatives. This means that there were instances where the model incorrectly classified patients as having or not having heart disease. Therefore, although accuracy is high, we should consider other metrics such as precision and recall for a more comprehensive assessment of the model.
