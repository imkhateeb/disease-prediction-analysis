## 🩺 Diabetes Disease Prediction using Machine Learning

A data science project to predict the likelihood of diabetes in patients using various machine learning models. It includes **data cleaning**, **exploratory data analysis (EDA)**, **model training**, **evaluation**, and **hyperparameter tuning** to achieve maximum accuracy.

---
[Demo](https://glucogrd.vercel.app/)
---

### 📁 Dataset

- **Source**: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (0 = Non-diabetic, 1 = Diabetic)

---

### 📊 Project Highlights

- Data cleaning (handling missing values & outliers)
- Exploratory Data Analysis (correlation, age distribution)
- Model building:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - Decision Tree
  - K-Nearest Neighbors (KNN)
- Confusion matrices and classification reports for each model
- Hyperparameter tuning using `GridSearchCV`
- Model performance comparison via bar chart

---

### 📌 Requirements

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

---

### 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/imkhateeb/disease-prediction-analysis
cd disease-prediction-analysis
```

2. Run the Jupyter Notebook for interactive visualization.

---

### 📈 Sample Output

- Accuracy of all models printed
- Confusion matrices displayed per model
- Final accuracy comparison plot
- Best hyperparameters shown for best model

---

### 📷 Visualizations

- Age vs Outcome Bar Charts
- Correlation Heatmaps
- Confusion Matrices
- Model Accuracy Comparison Bar Plot

---

### 🧠 Best Model

The best-performing model on the cleaned dataset is **Logistic Regression** with **~77% accuracy**, depending on the final cleaned data distribution.

---

### 🛠️ Future Improvements

- Deploy via **Streamlit** or **Flask**
- Include **ROC-AUC**, **Precision-Recall Curves**
- Add **Deep Learning** with TensorFlow or PyTorch
- Integrate with a **medical assistant web app**
