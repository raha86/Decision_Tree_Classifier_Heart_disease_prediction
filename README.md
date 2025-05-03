# Heart Disease Prediction - Decision Tree Classification

Dataset Link: https://drive.google.com/file/d/1cPJaFQfZKFvnD8yjpSFvsNxdttJwc-SE/view?usp=sharing

## About Dataset
* Attribute Information:
1. age
2. sex
3. cp: chest pain type (4 values)
4. trestbps: resting blood pressure
5. chol: serum cholestoral in mg/dl
6. fbs: fasting blood sugar > 120 mg/dl
7. restecg: ECG ( Electrocardio graphy ) level at resting
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina
10. oldpeak: How much ECG changes dusring exercise as compared to rest
11. slope: the slope of the peak exercise ST segment
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: ( thalassemia ) A blood disorder that can damage your heart
14. target

Build a model to predict heart disease based on the given dataset.

## Steps Performed:
1. Explored the dataset:
* Checked for duplicate rows
* Checked for null values
* Checked distribution of independent variables
  ![image](https://github.com/user-attachments/assets/31bceda1-a855-42a7-a7b3-8dcc129bcc29)
* Checked outliers using boxplot. As decision tree is very robust to outliers, we did not remove outlier.
  ![image](https://github.com/user-attachments/assets/e088537c-957f-4d06-9813-a5784f4b34e0)
* Checked correlation of independent variables with target variable.
  ![image](https://github.com/user-attachments/assets/9f7fcdf9-7298-49e4-8cf4-c3772b2584f3)
2. Model Building
  ![image](https://github.com/user-attachments/assets/d2de7bd7-732e-4cdc-9f88-f568fd1e66f9)

3. Model Evaluation:
* Used Accuracy Score to evaluate the model. Also used Confusion matrix to interpret the accuracy score.
  ![image](https://github.com/user-attachments/assets/c1edbff9-e09d-4d7a-a9c4-e4dfb95215a4)

* Achieved accuracy score 0.78
