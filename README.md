
# 🏦 Loan Default Prediction Model

A machine learning project to predict whether a loan applicant is likely to default. This model can help financial institutions make data-driven lending decisions and reduce risk.

---

## 📌 Project Overview

This project builds a classification model to predict loan default using historical financial and customer data. Multiple machine learning algorithms were explored, with **XGBoost** achieving the best performance after hyperparameter tuning.

---

## ⚙️ Tech Stack

* **Python**
* **Pandas** – Data manipulation and preprocessing
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Model building, preprocessing, and evaluation
* **XGBoost** – Final optimized model
* **LightGBM (LGM)** – Comparative modeling
* **Pickle** – Model serialization

---

## 📊 Workflow

1. **Data Preprocessing**

   * Handled missing values
   * Encoded categorical variables
   * Feature scaling (if required)

2. **Exploratory Data Analysis (EDA)**

   * Visualized distributions and correlations
   * Identified key patterns and risk indicators

3. **Model Training**

   * Trained multiple models:

     * Logistic Regression
     * Random Forest
     * LightGBM
     * XGBoost

4. **Model Optimization**

   * Hyperparameter tuning performed on **XGBoost**
   * Achieved best performance among all models

5. **Evaluation Metrics**

   * Accuracy
   * Precision
   * Recall
   * F1 Score
   * ROC-AUC

---

## 🚀 Best Model

✅ **XGBoost (Tuned)**

* Delivered the highest performance
* Optimized using hyperparameter tuning techniques
* Selected as the final production model

---

## 💾 Model Saving

The trained model is saved using **Pickle** for easy deployment:

```python
import pickle

with open('loan_default_model.pkl', 'wb') as file:
    pickle.dump(model, file)
```

To load the model:

```python
with open('loan_default_model.pkl', 'rb') as file:
    model = pickle.load(file)
```

---

## 📁 Project Structure

```
├── data/
├── notebooks/
├── models/
│   └── loan_default_model.pkl
├── src/
├── README.md
└── requirements.txt
```

---

## 📈 Future Improvements

* Deploy model using Flask/FastAPI
* Add real-time prediction interface
* Improve feature engineering
* Use cross-validation for robustness

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👤 Author

Your Name
(Replace with your GitHub profile link)

---
