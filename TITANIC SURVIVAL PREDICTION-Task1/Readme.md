
# 🚢 Titanic Survival Prediction - Analysis Report

## 📌 Introduction
This report provides an analysis of the Titanic dataset to predict passenger survival using machine learning. The dataset includes features such as age, gender, ticket class, fare, and embarkation details.

## 🔍 Data Preprocessing
### ✅ Checking for Missing Values
- Missing values were found in `Age`, `Cabin`, and `Embarked` columns.

### 🔄 Handling Missing Values
- `Age`: Filled with the median age.
- `Embarked`: Filled with the most frequent value (mode).
- `Cabin`: Dropped due to a high percentage of missing values.

### ✂️ Removing Unnecessary Columns
- Dropped `Name`, `Ticket`, and `PassengerId` as they are not useful for prediction.

## 📊 Exploratory Data Analysis (EDA)
- **Survival Rate by Class**: Higher survival rate in first-class passengers.
- **Survival Rate by Gender**: Higher survival rate for females.
- **Age Distribution**: Majority of passengers were between 20-40 years old.

## 🔠 Feature Encoding
- Converted categorical variables (`Sex` and `Embarked`) into numerical values using Label Encoding.

## ✂️ Data Splitting
- Split into **70% training data** and **30% validation data**.
- Used stratified sampling to ensure an even distribution of survival labels.

## 🤖 Model Training
- Used **Random Forest Classifier** with `n_estimators=100`.
- Trained the model using the processed dataset.

## 📉 Model Evaluation
- **Training Accuracy**: 80%
- **Predicted Accuracy on Training Data**: 76%
- **Test Accuracy**: 79%
- **Predicted Test Accuracy**: 72%
- **Confusion Matrix**:
  - ✅ True Positives: 55
  - ✅ True Negatives: 92
  - ❌ False Positives: 13
  - ❌ False Negatives: 19
- **Classification Report**:
  - Precision and Recall were higher for non-survivors.

## 🚀 Future Improvements
- Hyperparameter tuning to improve model performance.
- Exploring models like Logistic Regression or XGBoost.
- Adding feature engineering, such as a `Family Size` feature.

## 🏁 Conclusion
The model achieved **79% test accuracy**, with better recall for non-survivors. Further optimizations can enhance predictive performance.

---
This report summarizes the data analysis and machine learning approach taken for the Titanic survival prediction project.

