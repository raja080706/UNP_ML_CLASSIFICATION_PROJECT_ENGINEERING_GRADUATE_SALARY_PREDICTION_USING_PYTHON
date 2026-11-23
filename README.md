# UNP_ML_CLASSIFICATION_PROJECT_ENGINEERING_GRADUATE_SALARY_PREDICTION_USING_PYTHON

1. Project Overview

This project aims to predict the salary category of engineering graduates using Machine Learning classification techniques. It uses the Engineering Graduate Salary dataset from Kaggle, containing 2,998 graduate records. The objective is to classify graduates into Low Salary and High Salary categories based on academic performance, engineering specialization, aptitude scores, technical skills, college information, and personality traits.

The original continuous salary variable was converted into a binary target using the mean salary of approximately ₹305,175. Salaries less than or equal to the mean were classified as Low Salary, while salaries above the mean were classified as High Salary.

 2. Machine Learning Implementation

The implementation involved data preprocessing, feature engineering, exploratory data analysis, and model development. Unnecessary columns were removed, unavailable technical assessment scores were handled, and age was derived from date of birth. Specialization names were standardized and grouped into broader engineering streams. Categorical features were converted into numerical form using suitable encoding techniques.

Ten classification algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gaussian Naive Bayes
- AdaBoost
- Gradient Boosting
- XGBoost
- Artificial Neural Network (ANN)

Hyperparameter tuning was performed on selected models using Grid Search with 5-fold cross-validation. Additionally, ten ANN architectures were experimented with to identify a suitable network based on validation accuracy.

 3. Model Evaluation

The models were evaluated and compared using different train-test split ratios. Performance was assessed using Accuracy, Precision, Recall, F1-score, ROC-AUC, and Confusion Matrix. These metrics helped measure overall prediction correctness, the quality of High Salary predictions, and the model's ability to distinguish between the two salary categories.

The results showed that ensemble methods such as Gradient Boosting, Random Forest, and XGBoost achieved competitive performance. ANN experiments also demonstrated how different network architectures influenced prediction results. Overall, the project compares multiple Machine Learning approaches to identify patterns associated with engineering graduates' salary categories.

This is the link for classification project google colab file
https://drive.google.com/file/d/1pzO4RyCud_NACwp8YMTXntRtba1DXoFE/view?usp=sharing

This is the link for classification project presentation
https://docs.google.com/presentation/d/1yZRL2Run1mnEGAq5_Kmt22m533J-E8Ib/edit?usp=sharing&ouid=117163424557360481126&rtpof=true&sd=true
