# 🌾 Farmer Technology Adoption Prediction

This project predicts whether a farmer is likely to adopt a new agricultural technology based on socio-economic and farm-level factors. Using a Random Forest Classifier and hyperparameter tuning, the model achieves high accuracy in classifying adoption behavior. This solution can help policymakers, agritech companies, and researchers identify target groups for intervention and resource allocation.

---

## 📌 Problem Statement

Understanding the determinants of technology adoption among farmers is crucial for increasing agricultural productivity and sustainability. This project uses supervised machine learning to classify farmers as **Adopters** or **Non-Adopters** based on features such as income, age, farm size, education, access to extension services, and more.

---

## 🔍 Dataset Overview

- **Source**: Primary data collected from a sample of farmers
- **Target Variable**: `Adoption Status` (1 = Adopter, 0 = Non-Adopter)
- **Features** include:
  - Age, Education, Income, Farm Size
  - Access to credit
  - Contact with extension agents
  - Group membership
  - Years of farming experience
  - and more...

---

## 🧠 Model Used

- **Random Forest Classifier** from `scikit-learn`
- Hyperparameter tuning using `RandomizedSearchCV`
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix

---

## ⚙️ Technologies and Tools

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- Joblib (for model serialization)

---

## 📈 Model Performance

| Metric          | Value     |
|-----------------|-----------|
| Accuracy        | 73.5%     |
 


> 📌 Confusion matrix and feature importance plots included in the `notebooks/` directory.

---

## ✅ Key Highlights

- ✅ Cleaned and preprocessed a near-balanced dataset (253 adopters / 235 non-adopters)
- ✅ Used `class_weight='balanced'` to account for slight imbalance
- ✅ Performed RandomizedSearchCV to optimize RF hyperparameters
- ✅ Visualized results and interpreted key influencing factors
- ✅ Model saved as `.pkl` for deployment/inference

---

## 📂 Project Structure

# farmer-tech-adoption-model
