# Anemia Detection with Machine Learning
---
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/clang) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/maladeep/anemia-detection-with-machine-learning)  ![GitHub](https://img.shields.io/github/license/maladeep/anemia-detection-with-machine-learning)
----
# Overview
This repo consist of python machine learning code for the detection of the anemi using the data from Kaggle, provided by the username Biswa Ranjan Rao, and the direct URL to the dataset is https://www.kaggle.com/datasets/biswaranjanrao/anemia-dataset.

The dataset consists of 1421 samples with six attributes: gender, hemoglobin, mean corpuscular hemoglobin (MCH), mean corpuscular hemoglobin concentration (MCHC), mean corpuscular volume (MCV), and result.

The result attribute(class), represented by the binary values 0 for non-anemic and 1 for anemic in the data set, was selected as the response variable. The gender attribute being binary, all other attributes were continuous variables, and the memory size consumed by the dataset was 66.7 MB.

---

## Introduction to Anemia
Anemia is a medical condition characterized by a deficiency of healthy red blood cells in the body or a reduction in the amount of hemoglobin in the blood. Hemoglobin is the protein in red blood cells responsible for carrying oxygen throughout the body. Anemia can occur due to various reasons such as a lack of iron or other essential nutrients, chronic diseases, genetic conditions, blood loss, or a malfunction in the bone marrow.

Symptoms of anemia include fatigue, weakness, shortness of breath, dizziness, pale skin, irregular heartbeat, and headaches. Treatment for anemia depends on the underlying cause, but it may involve dietary changes, supplements, medication, or, in severe cases, blood transfusions.

It is important to identify and treat anemia promptly, as it can lead to complications such as heart problems, impaired cognitive function, and delayed growth and development in children.

---

## What's Inside
1. Exploratory Data Analysis
2. Statistical test with t-test, Odd ratio, and Chi-square test for association
3. Feature Selection
   * Correlation
   * SelectKBest 
   * Extra Tree Classifier
4. Scaling feature
   * log 
   * Standardization
   * Normalization
5. Class imbalance handling
   *  Random Undersampling
   *  Random Oversampling
   *  SMOTE
   *  ADASYN
6. Data Leakage handling
7. Algorithms employed
   * Decision Tree (DT)
   * Random Forest (RF)
   * Logistic Regression (LG)
   * K-Nearest Neighbors (KNN)
   * Support Vector Machine (SVM)
   * Gaussian Naive Bayes (NB)
8. Performance measured
   * Accuracy
   * Area Under the Curve
   * Precision
   * Recall
   * F1 Score
   * Kappa Stat
9. Hyperparameter tuning with GridsearchCV
10. 5 fold cross validation

---
## Usages
[Run Live App](https://anemia-detection-with-machine-learning-b7llxt4qca.streamlit.app)
or run code -> streamlit anemia.py
## Contributing

Contributions are what makes the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.
## Project Photo

![image](https://github.com/user-attachments/assets/cfdc3bd6-8b6e-410d-bc7c-a65541a71072)

![image](https://github.com/user-attachments/assets/24160063-bcfe-4200-9ad1-fa7e58fc43b8)

![image](https://github.com/user-attachments/assets/c9908bc8-9f22-4ac4-bbbe-89a11411cea0)

![image](https://github.com/user-attachments/assets/ce0131fa-099f-41f4-80a9-a113ef418c00)

![image](https://github.com/user-attachments/assets/7f006c5f-fed9-4071-907d-d6c5c1aebdd7)

![image](https://github.com/user-attachments/assets/f4b7eb2c-afc2-477c-8d01-d58db75b4aa6)

Contact me : 0587282880 ( phone & zalo ) - my email address: ducvan05102002@gmail.com
Thanks. Now U can give me a star <33





---
