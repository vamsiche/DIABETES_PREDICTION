# 🩺 Diabetes Prediction System

A machine learning–based classification system that predicts the likelihood of diabetes using medical and lifestyle attributes. This project demonstrates a complete ML pipeline including data preprocessing, feature engineering, model training, evaluation, and result interpretation.

---

## 📌 Features

- Binary classification (Diabetes: Yes / No)
- Data cleaning and preprocessing
- Feature scaling and encoding
- Multiple ML models for comparison
- Model evaluation using standard classification metrics
- Reproducible Jupyter Notebook workflow

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Each model is evaluated and compared to identify the most effective approach.

---

## 🛠️ Tech Stack

### Programming Language
- Python 3.x

### Libraries & Frameworks
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Environment
- Jupyter Notebook

---

## 📂 Project Structure

```
DIABETES_PREDICTION/
│
├── classification_prac.ipynb
├── diabetes_prediction_dataset.csv
├── README.md
```

---

## 📊 Dataset Information

### Target Variable
- diabetes  
  - 0 → Non-diabetic  
  - 1 → Diabetic  

### Input Features
- Age
- Gender
- Body Mass Index (BMI)
- Hypertension
- Heart Disease
- Smoking History
- HbA1c Level
- Blood Glucose Level

---

## ⚙️ Workflow Overview

1. Load and inspect the dataset
2. Handle missing values and inconsistencies
3. Encode categorical variables
4. Scale numerical features
5. Split data into training and testing sets
6. Train multiple classification models
7. Evaluate models using performance metrics
8. Compare results and analyze feature importance

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/vamsiche/DIABETES_PREDICTION.git
```

### 2. Navigate to Project Directory
```bash
cd DIABETES_PREDICTION
```

### 3. Open Jupyter Notebook
```bash
jupyter notebook classification_prac.ipynb
```

---

## 📌 Results & Insights

- Feature scaling improves performance
- Random Forest performs best among tested models
- Blood glucose and HbA1c are key predictors

---

## ⚠️ Limitations

- Limited dataset size
- No hyperparameter tuning
- Class imbalance not addressed

---

## 🔮 Future Enhancements

- Hyperparameter tuning (GridSearchCV)
- SMOTE for class imbalance
- Model deployment (Flask / FastAPI)
- Cross-validation and ROC–AUC

---

## 📄 License

Educational use only.

---

## 📬 Contact

GitHub: https://github.com/vamsiche
