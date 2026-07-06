# ❤️ Heart Disease Prediction using Logistic Regression

A Machine Learning project that predicts whether a patient is likely to have heart disease using the **Logistic Regression** algorithm. This project was developed in **Google Colab** using Python and the Scikit-learn library as part of a Machine Learning internship.

---

# 📖 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors make timely decisions and improve patient care.

In this project, a Logistic Regression model is trained using patient medical data to predict whether a person is likely to have heart disease.

---

# 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Visualize important patterns in the dataset
* Build a Logistic Regression model
* Evaluate model performance
* Predict heart disease for new patient data

---

# 🛠️ Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📂 Dataset

The dataset contains medical information collected from patients.

### Features

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate (thalach)
* Exercise Induced Angina (exang)
* Oldpeak
* Slope
* Number of Major Vessels (ca)
* Thalassemia (thal)

### Target Variable

* **0** → No Heart Disease
* **1** → Heart Disease

* ### Dataset Source

The dataset is based on the **UCI Heart Disease Dataset**, which is commonly used for educational purposes and machine learning classification tasks.

---

# 📊 Exploratory Data Analysis (EDA)

The following visualizations were created:

* Heart Disease Distribution
* Age Distribution
* Gender Distribution
* Correlation Heatmap
* Chest Pain Type vs Heart Disease
* Cholesterol Distribution
* Maximum Heart Rate Distribution
* Box Plot
* Feature Importance
* Confusion Matrix
* ROC Curve

---

# 🤖 Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for binary classification problems. It predicts whether a patient belongs to one of two classes:

* Heart Disease
* No Heart Disease

---

# 📈 Model Performance

| Metric            | Score      |
| ----------------- | ---------- |
| Training Accuracy | **84.88%** |
| Testing Accuracy  | **81.46%** |

The small difference between training and testing accuracy indicates that the model generalizes well and does not suffer from significant overfitting.

---


# 🔄 Project Workflow

```text
Load Dataset
      │
      ▼
Data Exploration (EDA)
      │
      ▼
Data Visualization
      │
      ▼
Feature Selection
      │
      ▼
Train-Test Split
      │
      ▼
Logistic Regression
      │
      ▼
Prediction
      │
      ▼
Model Evaluation
      │
      ▼
Heart Disease Prediction
```

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction-Using-Logistic-Regression.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook using **Google Colab** or **Jupyter Notebook**.

---

# 📁 Project Structure

```text
Heart-Disease-Prediction-Using-Logistic-Regression/
│
├── Heart_Disease_Prediction_Using_Logistic_Regression.ipynb
├── heart.csv
├── README.md
├── LICENSE
└── Graph/
    ├── heatmap
    ├── confusion_matrix
    ├── roc_curve
    ├── feature_importance
```

---

# 🚀 Future Improvements

* Hyperparameter tuning
* Compare Logistic Regression with Random Forest and XGBoost
* Build a Streamlit web application
* Deploy the model online
* Improve model performance using feature engineering

---

# 👨‍💻 Author

**Pawan Kumar Koiri**

B.Tech in Computer Science Engineering

Machine Learning Enthusiast

---

⭐ If you found this project useful, consider giving it a **star** on GitHub.

