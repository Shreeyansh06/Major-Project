#Customer Churn Prediction using Machine Learning

## 1. Project Title & Description

This project predicts customer churn using multiple machine learning models and advanced techniques like GridSearchCV and SHAP. It helps businesses identify customers likely to leave and take preventive actions.

---

## 2. Dataset

* **Source:** https://www.kaggle.com/blastchar/telco-customer-churn
* **Description:**
  The dataset contains customer demographic details, account information, and service usage patterns. The target variable is **Churn**, indicating whether a customer leaves the service.

---

## 3. Installation & Setup

Clone the repository:

```bash
git clone https://github.com/Sheeyansh06/customer-churn-prediction.git
cd customer-churn-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 4. How to Run

Run the main script:

```bash
python src/Data_Processing.py
```

(Optional – Jupyter Notebook):

```bash
jupyter notebook notebooks/churn_analysis.ipynb
```

---

## 5. Results Summary

* **Best Model:** Random Forest Classifier
* **Key Metrics:**

  * Accuracy: ~85–90%
  * ROC-AUC Score: High (best among all models)
* **Key Insight:**
  Customers with **high monthly charges and low tenure** are more likely to churn.

---

## 6. Project Architecture

```
customer-churn-prediction/
│
├── data/                # Dataset files
├── src/                 # Core Python scripts
├── outputs/             # Saved plots and results
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

---

## 7. Tech Stack

* **Python** – Core programming language
* **Pandas & NumPy** – Data manipulation and processing
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models and evaluation
* **Imbalanced-learn (SMOTE)** – Handling class imbalance
* **SHAP** – Model explainability

---

## Conclusion

This project demonstrates a complete machine learning pipeline from data preprocessing to model evaluation and interpretation, making it suitable for real-world business applications.

