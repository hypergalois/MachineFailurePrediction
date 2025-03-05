# Machine Failure Detection with PCA and Classification 🚀

## 1. **Exploratory Data Analysis (EDA)** and Data Preprocessing

![SQLITE](img/1.png "SQLITE DB")

- **Handling missing values**: Imputation techniques were used to replace missing values in key features.
- **Encoding categorical variables**: One-Hot Encoding was applied to categorical variables.
- **Normalization and scaling**: **PCA (Principal Component Analysis)** was used for dimensionality reduction and feature scaling.

![Correlation](img/2.png "Correlation")

![SMOTE](img/3.png "SMOTE")

## 2. **Model Selection** Using Multiple Classifiers (e.g., Logistic Regression, RandomForest, GradientBoosting, XGBoost)

- **Logistic Regression**: Used for classifying machine status.
- **Random Forest Classifier**: Utilizes multiple trees to handle complex feature relationships.
- **Gradient Boosting Classifier**: Boosting model to improve accuracy.
- **XGBoost Classifier**: An advanced boosting model optimized for speed and efficiency.

**PCA** was used to reduce feature dimensionality and improve model performance.

![Explained Variance](img/4.png "Explained Variance")

![Model screenshot](img/5.png "Modeling Overview")

## 3. **Metrics Calculation** for Each Model

- **Precision**: The proportion of correctly predicted positive cases.
- **Recall**: The proportion of true positives over the total actual positive cases.
- **F1 Score**: The harmonic mean of precision and recall.
- **Accuracy**: The proportion of correct predictions overall.
- **Confusion Matrix**: To visualize true positives, false positives, etc.

![Metrics screenshot](img/6.png "Evaluation Results")
