💳 Credit Card Fraud Detection 💰
------------------------------------
![image](https://github.com/pdannana/code-clause-interhsip-_Fraud-Detection/assets/95438767/280879ec-19a9-473d-80d0-29511b12f607)

                          

This project focuses on detecting fraudulent transactions in a credit card dataset using anomaly detection and classification algorithms. The goal is to identify potentially fraudulent activities, enhancing security and reducing financial losses for credit card companies.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Technologies Used
Python: Programming language used for the project.
Pandas: Data manipulation and analysis library.
Scikit-learn: Machine learning library for building models.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://github.com/pdannana/code-clause-interhsip-_Fraud-Detection/assets/95438767/26dcfd5d-273e-411f-9b52-0cdcccb90a0c)

📊 Methods Used:

->Anomaly Detection
Isolation Forest: An algorithm that isolates observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature.
->Local Outlier Factor (LOF): A density-based algorithm that computes the local density deviation of a given data point with respect to its neighbors.
One-Class SVM: A support vector machine algorithm that learns a decision function for novelty detection: classifying new data as similar or different to the training set.
Classification
Logistic Regression: A linear model for binary classification that estimates probabilities using a logistic function.
->Random Forest: An ensemble learning method that constructs a multitude of decision trees during training and outputs the mode of the classes for classification.
Gradient Boosting: An ensemble technique that builds models sequentially, where each new model corrects errors made by the previous ones.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/pdannana/code-clause-interhsip-_Fraud-Detection/assets/95438767/d69c2fff-5445-48e6-8b78-a038b6cfc239)


🚀 How to Run This Project
Clone the project repository to your local machine.
Install the required libraries mentioned in the requirements.txt file using pip.
Copy code
pip install -r requirements.txt
Run the main Python script or Jupyter Notebook file to preprocess the data, train the model, and evaluate its performance.
View the results and analyze the model's effectiveness in detecting fraudulent transactions.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📋 Project Overview
Fraudulent transactions can lead to significant financial losses for credit card companies. By leveraging anomaly detection and classification algorithms, this project aims to build a robust fraud detection system that can identify and flag potentially fraudulent transactions.
