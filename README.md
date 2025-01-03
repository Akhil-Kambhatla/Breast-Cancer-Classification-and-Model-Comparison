# Breast-Cancer-Classification-and-Model-Comparison
This project uses a publicly available dataset to build machine-learning models to predict whether breast cancer cases are malignant or benign. The workflow involves data preprocessing, handling class imbalance, and evaluating multiple models to identify the best-performing algorithm.

Data Preprocessing:
1. Removed unnecessary columns and encoded the target variable.
2. Normalized features using StandardScaler.
3. Addressed class imbalance with SMOTE (Synthetic Minority Over-sampling Technique).

Models Trained:
1. Logistic Regression
2. Support Vector Machines (SVM)
3. Decision Tree Classifier
4. Random Forest Classifier

Performance Metrics:
Accuracy, Precision, Recall, ROC-AUC

Evaluation:
1. Comparison of models using bar plots for key metrics.
2. Visualization of ROC curves for models supporting probability predictions.
3. Automatic selection of the best model based on the average of all metrics.

Libraries:
1. scikit-learn: For model building and evaluation
2. imbalanced-learn: For handling class imbalance using SMOTE
3. matplotlib and seaborn: For data visualization
4. pandas: For data manipulation

Results:
Support Vector Machines (SVM) emerged as the best-performing model among the models evaluated. This highlights its capability in effectively distinguishing between malignant and benign breast cancer cases.
