# 07_Detect-Spam-Emails_202401100400067
Spam Email Detection using Logistic Regression
 Project Overview
 This project implements a logistic regression-based classifier to detect spam emails. The dataset is
 preprocessed, standardized, and used to train a binary classification model. Evaluation metrics like accuracy,
 precision, and recall are used to assess performance.
 Technologies Used- Python- Pandas & NumPy- Scikit-learn- Seaborn & Matplotlib- Logistic Regression
 Dataset
 The dataset includes email features and a target variable 'is_spam' labeled as 'yes' for spam (1) and 'no' for
 not spam (0).
 Implementation Steps
 1. Import libraries and load data.
 2. Encode target variable and preprocess features.
 3. Standardize features using StandardScaler.
 4. Split data into training and testing sets.
 5. Train Logistic Regression model.
 6. Predict on test set.
 7. Evaluate using confusion matrix, accuracy, precision, and recall.
Spam Email Detection using Logistic Regression
 Sample Results
 Accuracy: 0.94
 Precision: 0.91
 Recall: 0.89
 Confusion Matrix is visualized using Seaborn's heatmap.
 Future Improvements- Use more advanced ML models- Add NLP preprocessing for text features- Implement cross-validation- Enhance feature engineering
 Contact
 For queries or suggestions, please raise an issue on the GitHub repository.
