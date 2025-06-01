# CampusPulse: Exploring Student Life Through Data

**CampusPulse** is a strategic data analytics initiative developed in collaboration with the Student Wellness and Experience Board. The project analyzes anonymized student survey data to uncover meaningful patterns in academic, social, and behavioral life on campus — with a special focus on understanding the predictors of romantic relationships among students.

## 🔍 Project Objectives

This project is built around a series of investigative and modeling tasks designed to explore the connections between student lifestyle habits and their relationship status. It involves:
- Data forensics to identify anonymized survey features
- Ensuring data quality through imputation and cleanup
- Uncovering insights through visual exploratory data analysis (EDA)
- Predictive modeling to assess the likelihood of a student being in a romantic relationship
- Interpretable machine learning using SHAP and decision boundary visualizations

---

## 📁 Contents

- `data/`: Raw and cleaned datasets (with sensitive information anonymized)
- `notebooks/`: Jupyter notebooks for each major phase of the project
- `eda/`: Visualizations and insights from exploratory analysis
- `models/`: Classification models and evaluation metrics
- `shap_analysis/`: SHAP plots and interpretations for model explainability
- `utils/`: Custom functions for preprocessing, imputation, and visualization

---

## 🧠 Key Highlights

### 1. Feature Identification
- Used statistical patterns, histograms, and correlation heatmaps to reverse-engineer the identities of anonymized features (`Feature_1`, `Feature_2`, and `Feature_3`)
- Justified guesses based on domain intuition and quantitative relationships (e.g., correlation with known academic or behavioral features)

### 2. Data Cleaning
- Identified missing values and outliers
- Applied variable-specific imputation strategies such as median filling for numerical features and mode imputation for categorical responses
- Justified all imputation decisions based on distributional properties and feature importance

### 3. Exploratory Insights
Asked and answered key questions using the data:
- How does stress correlate with academic performance?
- Is social activity linked to relationship status?
- What role does screen time play in mental health?
- Are students who sleep more likely to report higher academic satisfaction?
- How does relationship status affect subjective happiness?

Each insight is backed by visualizations (bar plots, violin plots, scatter plots) and concise interpretations.

### 4. Relationship Prediction Model
- Built and compared several classification models: Logistic Regression, Random Forest, XGBoost
- Evaluated performance using accuracy, precision, recall, F1-score, and ROC-AUC
- Identified behavioral and academic predictors of romantic involvement

### 5. Model Explainability
- Visualized decision boundaries for key feature pairs
- Applied SHAP to:
  - Analyze global feature importance
  - Generate local explanations for individual predictions
- Translated SHAP outputs into plain language to uncover what truly drives the model's decisions

---

## 🛠 Tech Stack

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Seaborn, Matplotlib, Plotly)
- **Jupyter Notebooks**
- **Git & GitHub** for version control

---

## 🤝 Acknowledgements

Thanks to the Student Wellness and Experience Board for providing the anonymized dataset and guiding the direction of this analysis.

---

## 📬 Contact

For questions, collaboration, or feedback, feel free to reach out via GitHub or email.

