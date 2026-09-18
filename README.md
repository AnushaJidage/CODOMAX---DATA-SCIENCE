# 🎓 Student Success Predictor
### End-to-End Data Science & Machine Learning Project

> **Codomax Data Science Internship · Module 6 · Final Project**

A portfolio-ready Data Science project that explores student performance data, discovers meaningful patterns, and builds Machine Learning models to classify **Pass / Fail outcomes**.

---

## 🚀 Project at a Glance

| Item | Details |
|---|---|
| **Domain** | Education Analytics |
| **Project Type** | Classification |
| **Language** | Python |
| **Dataset** | Student Performance |
| **Models** | Logistic Regression · Random Forest |
| **Environment** | Google Colab |
| **Version Control** | GitHub |

---

## 🎯 Project Objective

The goal of this project is to demonstrate a complete Data Science workflow:

**Raw Data → Cleaning → EDA → Visualization → Feature Engineering → Machine Learning → Evaluation → Insights**

The project investigates student-related factors and develops models that predict whether a student is likely to **Pass** or **Fail**.

---

## 🧭 Project Workflow

```text
📥 Load Dataset
      ↓
🔍 Understand Data
      ↓
🧹 Clean & Validate
      ↓
📊 Exploratory Data Analysis
      ↓
📈 Visualize Patterns
      ↓
⚙️ Prepare Features
      ↓
✂️ Train / Test Split
      ↓
🤖 Train ML Models
      ↓
📏 Evaluate Performance
      ↓
💡 Interpret Results
      ↓
📦 Portfolio Output
```

---

## 🛠️ Tech Stack

### Data Analysis
- **Python**
- **Pandas**
- **NumPy**

### Visualization
- **Matplotlib**
- **Seaborn**

### Machine Learning
- **Scikit-learn**
- Logistic Regression
- Random Forest Classifier

### Development
- **Google Colab**
- **GitHub**

---

## 📊 Exploratory Data Analysis

The notebook explores questions such as:

- What does the Pass / Fail distribution look like?
- Does weekly study time differ across outcomes?
- How are previous failures associated with student success?
- Is attendance related to final performance?
- Do higher-education aspirations differ between student groups?
- Which numerical variables show stronger relationships with academic outcomes?

Visualizations include:

`Bar Charts` · `Histograms` · `Scatter Plots` · `Correlation Heatmap`

---

## 🤖 Machine Learning

### 1️⃣ Logistic Regression

Used as an interpretable baseline classification model.

### 2️⃣ Random Forest Classifier

Used to capture more complex relationships and examine feature importance.

Both models follow the same reproducible pipeline:

```text
Features
   ↓
Preprocessing
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Evaluation
```

---

## 📏 Evaluation Metrics

Model performance is evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **ROC-AUC**
- **Confusion Matrix**

The results of both models are summarized in:

📄 `model_comparison.csv`

---

## 🧠 Important Modeling Decision

The final grade **G3** directly determines the Pass/Fail target, so it is excluded from model features to prevent **target leakage**.

The primary model also excludes **G1** and **G2** so that predictions rely more on broader student characteristics rather than previous grades that are already closely related to the final result.

---

## 🔎 Feature Importance

The Random Forest model is used to inspect which features contribute most strongly to its predictions.

Feature-importance results are exported to:

📄 `feature_importance.csv`

> Feature importance describes how the model uses variables for prediction. It should **not** be interpreted as proof that a feature causes a student outcome.

---

## 📁 Repository Structure

```text
Module-6-Final-Project/
│
├── 📓 Codomax_Module_6_Final_Data_Science_Project.ipynb
├── 📘 README.md
├── 📊 student_performance_final_cleaned.csv
├── 📈 model_comparison.csv
└── 🔎 feature_importance.csv
```

### File Guide

**`Codomax_Module_6_Final_Data_Science_Project.ipynb`**  
Main end-to-end notebook containing analysis, visualizations, preprocessing, ML models, evaluation, and conclusions.

**`student_performance_final_cleaned.csv`**  
Cleaned student-performance dataset used for project analysis.

**`model_comparison.csv`**  
Side-by-side evaluation of the Machine Learning models.

**`feature_importance.csv`**  
Random Forest feature-importance output.

---

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Open `Codomax_Module_6_Final_Data_Science_Project.ipynb`.
3. Upload/open it in **Google Colab**.
4. Run the notebook cells from top to bottom.
5. Review the EDA and visualization outputs.
6. Train Logistic Regression and Random Forest models.
7. Review the evaluation metrics.
8. Export the generated CSV outputs.

---

## 💡 Key Learning Outcomes

Through this final project, I practiced:

✅ Real-world dataset handling  
✅ Data quality assessment  
✅ Data cleaning  
✅ Exploratory Data Analysis  
✅ Data visualization  
✅ Feature preparation  
✅ Categorical encoding  
✅ Numerical scaling  
✅ Train/test splitting  
✅ Classification modeling  
✅ Model evaluation  
✅ Model comparison  
✅ Feature importance  
✅ Responsible interpretation of results  
✅ GitHub portfolio preparation  

---

## ⚠️ Limitations & Responsible Use

This project is designed for **learning and portfolio demonstration**.

The dataset represents a limited student population, and academic outcomes are influenced by many social, educational, personal, and contextual factors.

Therefore:

- Correlation does not imply causation.
- Model predictions should not be treated as definitive judgments about students.
- Performance on this dataset may not generalize to other populations.
- Educational predictions should support—not replace—human judgment.

---

## 🌱 What I Learned

This project helped connect the individual skills learned throughout the internship:

**Python → Data Analysis → Visualization → Machine Learning → Evaluation → Communication**

Instead of treating these as separate topics, Module 6 brings them together into one complete Data Science project.

---

## 🏁 Internship Milestone

**Codomax Data Science Internship**  
**Module 6 — Final Data Science Project**

### Author
**GitHub:** `chai0405-hub`

---

### ⭐ Project Status

**Completed · Portfolio Ready**

*Thanks for visiting this project!*
