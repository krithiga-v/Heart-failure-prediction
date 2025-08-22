# ❤️ Heart Failure Prediction

An **AI-powered machine learning project** that predicts the **likelihood of heart disease** based on patient health attributes.  
This project uses **ensemble learning** with Logistic Regression, Random Forest, and Gradient Boosting to achieve better prediction accuracy.

---

## ✨ Features

- 📊 **Data Exploration & Visualization**
  - Histograms, count plots, and correlation heatmaps.
- 🧠 **Machine Learning Models**
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - Soft Voting Classifier (Ensemble)
- 🎯 **Model Evaluation**
  - Accuracy score
  - Precision, recall, F1-score
  - Probability predictions for each model
- 🧾 **Interactive CLI Prediction**
  - Accepts patient data as **user input** and predicts the **risk of heart disease**.

---

## 🛠️ Tech Stack

- **Language** → Python 3.9+
- **Libraries Used**:
  - `pandas` → Data manipulation
  - `numpy` → Numerical computations
  - `seaborn` & `matplotlib` → Visualization
  - `scikit-learn` → Preprocessing, ML models, evaluation
  - `xgboost` *(optional if you want to extend models later)*

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/krithiga-v/Heart-failure-prediction.git
cd Heart-failure-prediction
2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Prepare the Dataset

Place your dataset in the project directory.

Update the dataset path in the script if necessary:

df = pd.read_csv("heart.csv")

4️⃣ Run the Script
python heart_failure_prediction.py
