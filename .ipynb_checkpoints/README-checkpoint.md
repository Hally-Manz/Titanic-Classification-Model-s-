# Titanic-Classification-Model-s-
Predicting Titanic passenger survival using machine learning. Used Logistic Regression and Decision Tree Classifiers/Estimators.

# Titanic Passenger Survival Prediction

A machine learning project built with **Scikit-Learn** to predict passenger survival on the Titanic based on features like age, gender, socio-economic status, and ticket information. 

This project explores the complete data science workflow: data cleaning, exploratory data analysis (EDA), feature engineering, model selection, and hyperparameter tuning.

## 📌 Project Overview
The sinking of the Titanic is one of the most infamous shipwrecks in history. Using a dataset containing details about 891 passengers, the goal of this project is to build a classification model that accurately predicts whether a given passenger survived or died.

### Key Highlights
* **Problem Type:** Binary Classification
* **Target Variable:** `Survived` (0 = No, 1 = Yes)
* **Core Tools:** Python, Scikit-Learn, Pandas, NumPy, Matplotlib.

---

## 🛠️ Installation & Setup
To run this project locally, clone this repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/Hally-Manz/Titanic-Classification-Model-s-.git

# Navigate to the project directory
cd Titanic-Classification-Model-s-

# Install dependencies
pip install (the libraries if not installed)
```

---

## 📊 Data Pipeline Workflow

### 1. Data Cleaning & Preprocessing
* **Categorical Encoding:** Converted categorical text column (`Sex` into numerical values using Scikit-Learn's `OneHotEncoder`).

### 2. Feature Engineering
* Dropped the `Name` column, it has no effect on our target variables.

### 3. Model Training & Evaluation
Trained and evaluated multiple classification algorithms from Scikit-Learn:
* **Logistic Regression** (Baseline model)
* **Decison Tree Classifier**

---

## 📈 Results & Performance

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| Logistic Regression | 77.00% | 82.00% | 80.00% | 81.00%|
| **Decision Tree** | **80.00%** | **78.00%** | **93.00%** | **85.00%** |


### Conclusion
The **Decison Tree Classifier** achieved the highest accuracy. Feature importance analysis showed that **gender (`Sex`)**, **passenger class (`Pclass`)**, and **fare** were the strongest predictors of survival.

---

## 👥 Author
* **Manzuma Halimat Jumai** - [GitHub Profile](https://github.com/Hally-Manz)