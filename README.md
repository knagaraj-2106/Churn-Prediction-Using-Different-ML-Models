# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

This project focuses on building a **machine learning model to predict customer churn** using structured customer data. The goal is to identify customers who are likely to leave a service, enabling businesses to take proactive retention actions.

The project demonstrates a complete **end-to-end ML pipeline**, including data preprocessing, feature engineering, model training, and evaluation.

---

## 📂 Dataset Description

The dataset contains customer-related information such as:

* Demographics (Gender, Senior Citizen, Dependents)
* Account details (Tenure, Contract type)
* Services used (Internet, Phone, Streaming, etc.)
* Billing information (MonthlyCharges, TotalCharges)
* Target variable:

  * **Churn (Yes / No)**

---

## ⚙️ Steps Performed

### 🔹 Data Preprocessing

* Loaded dataset into a DataFrame
* Handled missing values by replacing with appropriate values
* Converted categorical variables into usable format
* Checked and cleaned inconsistent data entries

---

### 🔹 Exploratory Data Analysis (EDA)

* Analyzed distributions of features
* Identified patterns related to churn behavior
* Visualized relationships between features and target variable

---

### 🔹 Feature Engineering

* Encoded categorical features
* Selected relevant features for modeling
* Standardized numerical variables where required

---

### 🔹 Data Preparation

* Separated features (**X**) and target (**y**)
* Split dataset into:

  * Training set
  * Testing set

---

### 🔹 Model Building

* Implemented classification models using **scikit-learn**
* Trained model on processed dataset
* Tuned hyperparameters to improve performance

---

### 🔹 Model Evaluation

* Evaluated model using:

  * Accuracy Score
  * Confusion Matrix
* Compared performance on training vs testing data

---

## 🤖 Predictive System

Developed a predictive system that takes **customer input features** and predicts:

* ✅ Customer will stay
* ❌ Customer will churn

---

## 🛠️ Technologies Used

* Python
* **pandas**
* **NumPy**
* **scikit-learn**
* Matplotlib / Seaborn

---

## 📊 Workflow

```text
Data Collection
↓
Data Cleaning
↓
EDA
↓
Feature Engineering
↓
Train-Test Split
↓
Model Training
↓
Model Evaluation
↓
Prediction System
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/knagaraj-2106/Churn-Prediction-Using-Different-ML-Models
```

2. Navigate to the project folder:

```bash
cd customer-churn-prediction
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the notebook or script:

```bash
jupyter notebook
```

---

## 📈 Results

* Built a reliable churn prediction model
* Achieved strong classification performance
* Demonstrated complete ML workflow from data to prediction

---

## 📌 Future Improvements

* Deploy model using API (FastAPI)
* Add real-time prediction system
* Use advanced models (XGBoost, Deep Learning)
* Implement model monitoring

---

## 👨‍💻 Author

**Nagaraj Kamale**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

