#  Diabetes Prediction - Classification Models

A machine learning project that predicts whether a person has diabetes using multiple classification algorithms.

---

##  Dataset

- **Source:** [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) on Kaggle
- **Features:** gender, age, hypertension, heart disease, smoking history, BMI, HbA1c level, blood glucose level
- **Target:** diabetes (0 = No, 1 = Yes)

> The dataset is downloaded automatically via `kagglehub` — no manual download needed.

---

##  Models Used

| Model | Library |
|-------|---------|
| K-Nearest Neighbors (KNN) | scikit-learn |
| Naive Bayes (Gaussian) | scikit-learn |
| Decision Tree | scikit-learn |
| SVM (Linear Kernel) | scikit-learn |

---

##  Project Workflow

1. **Import Libraries**
2. **Load Dataset** (via kagglehub)
3. **Encode Categorical Columns** (gender, smoking history)
4. **Exploratory Data Analysis (EDA)** — histograms, boxplots
5. **Handle Outliers**
6. **Remove Duplicates**
7. **Handle Missing Values**
8. **Correlation & Descriptive Statistics**
9. **Split Data** into training and testing sets
10. **Train & Evaluate** all 4 models

---

##  Evaluation Metrics

Each model is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

##  How to Run

1. Clone the repository:
```bash
git clone https://github.com/LamaOsama21/Diabetes-Prediction-Classification-Models.git
cd Diabetes-Prediction-Classification-Models
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook Diabetes_Prediction_Classification_Models.ipynb
```

>  Make sure you have a Kaggle account and your API key configured for `kagglehub` to work.

---

##  Requirements

See `requirements.txt` for all dependencies.

---

##  Author

Made with Lama Lubbad.
