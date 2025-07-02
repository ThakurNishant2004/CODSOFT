# CODSOFT
this repository is created for tasks submission

# 🚢 Titanic Survival Prediction

This is a classic machine learning project using the Titanic dataset to predict whether a passenger survived the Titanic shipwreck. The dataset contains features like age, sex, ticket class, and fare, and the task is to build a classification model to predict the `Survived` outcome (0 or 1).

---

## 📁 Dataset

The dataset used is from the [Kaggle Titanic dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset?resource=download):

- `train.csv`: contains the training data with labels
- `test.csv`: for optional testing without survival labels
- Target column: `Survived` (0 = Not Survived, 1 = Survived)

---

## 🧠 Objective

Build and evaluate a machine learning model to predict passenger survival based on the given features.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**  
  - `pandas`  
  - `numpy`  
  - `matplotlib`, `seaborn` (for visualization)  
  - `scikit-learn` (for model training and evaluation)

---

## 🔎 Exploratory Data Analysis (EDA)

Visualizations created include:

- Survival count
- Survival by sex and passenger class
- Age and fare distribution
- heatmap
- Correlation

---

## ⚙️ Preprocessing Steps

- Dropped unnecessary columns: `Cabin`, `Ticket`, `Name`
- Handled missing values (`Age`, `Embarked`)
- Encoded categorical variables (`Sex`, `Embarked`)
- Feature scaling (optional)
- Train/test split for validation

---

## 🤖 Model Used

- **Linear Regression**
- Accuracy and classification report evaluated on the test set

---

## 📈 Results

- Classification accuracy: `43.5%` (replace with your actual score)
- Important features: `Sex`, `Pclass`, `Fare`, `Age`


---

## 🔍 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/titanic-survival-prediction.git

