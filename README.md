# Early-Coronary-Heart-Disease-Prediction-Using-Boruta-and-Smote
This project aims to develop a machine learning model to predict early coronary heart disease using the Boruta feature selection algorithm and the SMOTE (Synthetic Minority Over-sampling Technique) algorithm for handling imbalanced data. The goal is to provide a tool that can assist in the early detection and prevention of coronary heart disease.

Early Coronary Heart Disease Prediction using Boruta and SMOTE
This project aims to develop a machine learning model to predict early coronary heart disease using the Boruta feature selection algorithm and the SMOTE (Synthetic Minority Over-sampling Technique) algorithm for handling imbalanced data. The goal is to provide a tool that can assist in the early detection and prevention of coronary heart disease, enabling timely intervention and improved patient outcomes.

Table of Contents
Introduction
Data
Features
Methodology
Installation
Usage
Results
Contributing
License
Introduction
Coronary heart disease (CHD) is a leading cause of death worldwide, and early detection plays a crucial role in preventing its progression. This project focuses on developing a predictive model that can identify individuals at high risk of developing CHD in the early stages. By utilizing the Boruta feature selection algorithm and SMOTE for handling imbalanced data, the model aims to improve the accuracy and reliability of the predictions.

Data
The dataset used for this project consists of a collection of clinical and demographic features of individuals, along with their corresponding CHD status (positive or negative). The dataset is sourced from [provide source name or link here]. The features include various risk factors associated with CHD, such as age, gender, blood pressure, cholesterol levels, etc.

Features
The features used in this project include but are not limited to:

Age
Gender
Blood pressure
Cholesterol levels
Blood sugar levels
Body mass index (BMI)
Smoking status
Family history of CHD
Physical activity level
Methodology
Data Preprocessing: The dataset is cleaned and preprocessed to handle missing values, outliers, and any other inconsistencies. Feature engineering techniques may be applied to create new features or transform existing ones.
Feature Selection with Boruta: The Boruta algorithm is employed to identify the most relevant features for predicting early CHD. Boruta is a wrapper feature selection method that compares the importance of each feature against that of randomly generated shadow features.
Handling Imbalanced Data with SMOTE: Since CHD is often an imbalanced class, the SMOTE algorithm is utilized to generate synthetic samples of the minority class (positive CHD cases) to balance the dataset. SMOTE helps prevent bias towards the majority class during model training.
Model Training and Evaluation: A machine learning model (e.g., logistic regression, random forest, or gradient boosting) is trained using the selected features and the SMOTE-balanced dataset. The model's performance is evaluated using appropriate metrics such as accuracy, precision, recall, and F1 score.
Predicting Early CHD: The trained model can be used to predict early CHD for new, unseen individuals. The model takes input values for the relevant features and outputs the probability or prediction of CHD.
