# Stroke-Prediction-Machine Learning-Project


## 📌 Overview  
This project demonstrates the complete process of developing a machine learning classification model
while tackling real-world data challenges such as outliers and class imbalance.

This project reflects my ability to:
Perform EDA and end-to-end data cleaning,data preprocessing and feature engineering
Build different Classification Models and hyperparameter tuning 
Handle common ML issues (outliers & imbalance)
Optimize and evaluate models for better real-world applicability  

The model was trained on a dataset with minority classes under-represented, requiring special preprocessing and tuning.

---

## ⚙️ Techniques Used  
- **EDA**: Barplots,Histograms, Boxplots, Countplot
- **Outlier Handling**: Capping using IQR
- **Class Imbalance**: SMOTE (Synthetic Minority Oversampling)  
- **Models**: Logistic Regression, Random Forest,SVM,Gradient Boosting, KNN Classification  
- **Hyperparameter Tuning**: GridSearchCV  

---

## 📊 Results  
- Logistic Regression with tuned parameters:
  - Both classes have good recalls
  - **Best Params**: `C=0.1, penalty='l2', solver='saga'`  
  - **Cross-validated F1-score**: ~0.82
  - **Test Accuracy**: ~0.80
- Random Forest Classifier
  - **Best Params**: `max_depth': None, 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 300`  
  - **Cross-validated F1-score**: ~0.95 
  - **Test Accuracy**: ~0.90
- Random Forest Classifier
  - **Best Params**: `learning_rate': 0.1, 'max_depth': 7, 'n_estimators': 300, 'subsample': 0.8`  
  - **Cross-validated F1-score**: ~0.96
  - **Test Accuracy**: ~0.93

- Model evaluation used:
  - Classification Report
  - Confusion Matrix  
  - Precision, Recall, F1-score, Accuracy   
