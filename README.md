# Fraud_Detection

📊 Project Overview
This capstone project focuses on detecting fraudulent credit card transactions using machine learning. The dataset consists of anonymized transaction records, where features have been transformed using Principal Component Analysis (PCA) to preserve confidentiality. A major challenge addressed in this project is the extreme class imbalance, with fraudulent transactions making up less than 0.2% of the data.

To handle this, SMOTE (Synthetic Minority Oversampling Technique) was applied to balance the training set, ensuring better model learning. Three classification models were trained and evaluated:

Logistic Regression

Random Forest Classifier

Gradient Boosting Classifier

Each model was assessed based on accuracy, precision, recall, F1-score, and ROC AUC score. Special focus was placed on recall, as missing a fraudulent transaction is costlier than flagging a normal one.

Key findings revealed that:

Gradient Boosting achieved the highest ROC AUC (0.9809) and strong recall.

Random Forest provided the best balance between precision and recall.

Logistic Regression struggled with precision and convergence due to data complexity.

Overall, the project demonstrates how data preprocessing, oversampling, and ensemble modeling can be combined to build an effective credit card fraud detection system that can assist banks in reducing financial losses and improving customer trust.
