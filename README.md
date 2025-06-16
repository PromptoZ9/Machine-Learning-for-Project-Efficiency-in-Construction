# Predicting Resource Allocation Efficiency in Lean Construction Projects using Machine Learning

This project aims to analyze construction resource data and build a machine learning model to predict **Resource Allocation Efficiency**. It integrates core concepts of **Lean Construction** and applies regression-based predictive modeling.

## 🔧 Tech Stack Used
- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Dataset Overview
The dataset contains construction project details including:
- Labor count
- Equipment used
- Material quantity
- Project duration
- Risk level
- Resource Allocation Efficiency (target)

## 📊 Project Workflow (Phase-based)
**Phase 1: EDA (Exploratory Data Analysis)**
- Identified feature correlations
- Visualized trends and distributions

**Phase 2: Data Preprocessing**
- Scaled numerical values using `StandardScaler`
- One-Hot Encoded categorical features

**Phase 3: Model Training**
- Trained 3 models: Linear Regression, Random Forest, XGBoost
- Evaluated with RMSE and R² score

**Phase 4: Hyperparameter Tuning**
- Improved Random Forest and XGBoost performance using `GridSearchCV`

**Phase 5: Feature Importance**
- Visualized top contributing features to prediction output

## 🧠 Key Insights
- Linear Regression outperformed other models with the lowest RMSE.
- Project Duration and Material Quantity were strong predictors.
- Effective resource allocation correlates closely with planned timelines and manpower distribution.

## 📌 Files Included
- `Lean_Construction_Analysis.ipynb` – Full notebook with code, EDA, modeling, and visualizations.
- `Predicting Resource Allocation Efficiency in Lean Construction Projects using Machine Learning.pdf` – Formal report version of this project.

## 🔗 GitHub Repo
> 📂 [Click here to view the code](https://github.com/PromptoZ9/Machine-Learning-for-Project-Efficiency-in-Construction.git)

## 🧾 License
This project is open for educational and personal portfolio purposes. Commercial use should seek prior approval.