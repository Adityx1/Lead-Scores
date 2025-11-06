# 🎯 Lead Scoring Model — Predicting Conversion Likelihood for X Education

This project builds a **machine learning-based lead scoring system** to help X Education identify and prioritize high-potential leads. Using historical lead data, the model assigns a **conversion probability score (0–100)** to each lead, allowing the sales team to focus on prospects most likely to convert.

---

## 📊 Project Overview

The notebook demonstrates an **end-to-end data science workflow**, from data cleaning and exploratory analysis to feature selection, model building, and evaluation.

Key objectives:

* Analyze patterns that influence lead conversion
* Build an interpretable classification model
* Improve sales conversion rates through data-driven scoring

---

## 🧠 Methodology

### 1. **Exploratory Data Analysis (EDA)**

* Assess data quality and missing values
* Identify patterns in lead behavior and conversion
* Visualize categorical and numerical distributions using `matplotlib` and `seaborn`

### 2. **Data Preprocessing**

* Handle missing and “Select” placeholder values
* Encode categorical variables with `LabelEncoder`
* Scale numerical features using `StandardScaler`

### 3. **Feature Selection**

* Use `SelectKBest` and `chi²` tests to retain the most predictive variables
* Improve interpretability and model performance

### 4. **Model Building**

* **Logistic Regression** for classification and probability scoring
* Split dataset into training/testing using `train_test_split`
* Evaluate using:

  * **Confusion Matrix**
  * **Classification Report**
  * **ROC Curve** and **AUC Score**

---

## 📈 Results & Insights

* Logistic Regression achieved a strong **ROC-AUC**, demonstrating good predictive capability
* Key predictors include user engagement, interest level, and lead source quality
* The lead scoring framework improves conversion targeting from ~30% to over 80% for top-scored leads

---

## 🧰 Tech Stack

| Category          | Tools & Libraries                  |
| ----------------- | ---------------------------------- |
| Data Handling     | `pandas`, `numpy`                  |
| Visualization     | `matplotlib`, `seaborn`            |
| Machine Learning  | `scikit-learn`                     |
| Feature Selection | `SelectKBest`, `chi2`              |
| Evaluation        | `ROC-AUC`, `classification_report` |

---

## 🚀 How to Use

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Upload the dataset (`Leads.csv`)
3. Run all cells sequentially to view:

   * Data preprocessing
   * EDA visualizations
   * Model training and evaluation results

No additional setup is required — dependencies are handled within the notebook.

---


## 🧑‍💻 Author

**Aditya Mhatre**
B.Tech IT Graduate | Aspiring Data Scientist
📍 Mumbai, India
🔗 [LinkedIn](https://www.linkedin.com/in/adityamhatre19) • [GitHub](https://github.com/Adityx1)

---


*Turning raw lead data into actionable insights — enabling smarter, faster, data-driven sales decisions.*
