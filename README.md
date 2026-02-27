# Titanic Dataset - Data Preprocessing Pipeline 🚢

## 📌 Project Objective
This project focuses purely on data preprocessing and feature engineering using the Titanic dataset. The goal is to transform raw data into a clean, model-ready dataset.

---

## 📂 Dataset Source
Kaggle Titanic Competition Dataset

Target Variable: Survived

---

## 🔧 Preprocessing Steps Performed

### 1️⃣ Handling Missing Values
- Filled missing Age values using median
- Filled missing Embarked values using mode
- Dropped Cabin column due to high missing percentage

### 2️⃣ Feature Selection
- Removed irrelevant columns: Name, Ticket

### 3️⃣ Encoding Categorical Variables
- Converted Sex into numerical format
- Applied encoding to Embarked

### 4️⃣ Feature Scaling
- Standardized numerical features (Age, Fare)

### 5️⃣ Output
- Generated clean dataset: `train_preprocessed.csv`
- Dataset is ready for machine learning models

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

## 📈 Why This Project?
Preprocessing is one of the most important steps in machine learning. This project demonstrates structured data cleaning and transformation workflow.

---

## 👤 Author
Avinash Chinta
