## End to End Machine Learning Project


**Problem Statement: Predicting Heart Disease**

**Background:**

Heart disease is one of the leading causes of death globally. Early detection and accurate diagnosis are crucial for effective treatment and prevention of heart-related complications. Various factors such as age, gender, chest pain type, blood pressure, cholesterol level, and other clinical parameters are known to influence the risk of heart disease.

**Objective:**

The objective of this project is to develop a predictive model that can accurately identify the presence or absence of heart disease based on clinical and demographic features.

**Dataset Description:**

The dataset contains clinical and demographic information of individuals who have undergone testing for heart disease. The features include age, gender, chest pain type, resting blood pressure, serum cholesterol level, fasting blood sugar level, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, thallium stress test result, and the target variable indicating the presence or absence of heart disease.

### Life cycle of Machine learning Project

- Understanding the Problem Statement
- Data Collection
- Data Checks to perform
- Exploratory data analysis
- Data Pre-Processing
- Model Training
- Choose best model

**Outcome:**

The ultimate goal is to develop a robust and interpretable predictive model that can assist healthcare professionals in early detection and risk assessment of heart disease, leading to improved patient outcomes and better healthcare management strategies.

---

This problem statement outlines the task of predicting heart disease based on clinical and demographic features and provides a roadmap for data analysis, model development, and interpretation. It emphasizes the importance of leveraging data-driven approaches to address critical healthcare challenges and improve patient care.


## DEFINITION OF TERMS

- age: Age of the individual (integer).
- sex: Gender of the individual (integer). Typically, 0 represents female and 1 represents male.
- cp: Chest pain type (integer). It could be categorized into different types such as 0 for typical angina, 1 for atypical angina, 2 for non-anginal pain, and 3 for asymptomatic.
- trtbps: Resting blood pressure (in mm Hg) (integer).
- chol: Serum cholesterol level in mg/dl (integer).
- fbs: Fasting blood sugar > 120 mg/dl (integer). Typically, 0 represents false and 1 represents true.
- restecg: Resting electrocardiographic results (integer). It could represent different values based on different ECG results.
- thalachh: Maximum heart rate achieved (integer).
- exng: Exercise-induced angina (integer). Typically, 0 represents no and 1 represents yes.
- oldpeak: ST depression induced by exercise relative to rest (float).
- slp: Slope of the peak exercise ST segment (integer).
- caa: Number of major vessels colored by fluoroscopy (integer).
- thall: Thallium stress test result (integer).
- output: Target variable indicating presence of heart disease (integer). Typically, 0 represents absence and 1 represents presence.
