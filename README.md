# Tags
#Regression #MLPipeline #Capstone #FeatureEngineering #ModelComparison #Python #ScikitLearn #DataScience #Jupyter #AutoML

# Final Assignment: Supervised Machine Learning - Car Price Prediction
This repository contains my final assignment demonstrating end-to-end supervised machine learning regression modeling for car price prediction. The project showcases comprehensive feature engineering, data cleaning, and multiple regression techniques including OLS, Ridge, and Lasso regression.
## Key Features
- Advanced data cleaning and preprocessing pipeline
- Comprehensive exploratory data analysis (EDA)
- Feature engineering and feature importance extraction
- Multiple regression model comparison (OLS, Ridge, Lasso)
- Pipeline-based model implementation with cross-validation
- Performance evaluation and model selection
- Jupyter Notebook (.ipynb) with complete analysis, code, and results
## Technical Skills Showcased
- **Machine Learning**: Supervised regression modeling, feature engineering, model comparison
- **Python Libraries**: pandas, scikit-learn, matplotlib, seaborn, numpy
- **Data Science**: End-to-end regression modeling pipeline, cross-validation, feature importance analysis
- **Statistical Methods**: OLS regression, Ridge regression, Lasso regression, regularization techniques
- **Data Analysis**: Advanced data cleaning, exploratory data analysis, statistical visualization
## Project Overview
This project demonstrates a complete machine learning workflow for predicting car prices based on various vehicle features. The analysis includes comprehensive data preprocessing, feature selection, model training with multiple regression techniques, and thorough evaluation using cross-validation methods.
## Author
Jimmie Williams
---
## 📊 Results
| Model  | RMSE  | MAE   | R²    |
|--------|-------|-------|-------|
| OLS    | 2500  | 1800  | 0.87  |
| Ridge  | 2420  | 1750  | 0.88  |
| Lasso  | 2520  | 1810  | 0.85  |
*Replace these with your values from `df_results` in the notebook.*
## 📈 Visualizations
- Correlation heatmap of features (see `results/corr_heatmap.png`)
- Feature importance bar chart (see `results/feature_importance.png`)
- Residuals plot and predicted vs. actual scatter
Place image files in a `results/` folder. To embed in Markdown:
```
![Correlation Heatmap](results/corr_heatmap.png)
```
## 🔎 Example Predictions
| Features (short) | Actual Price | Predicted Price |
| ---------------- | ------------ | --------------- |
| BMW, 4cyl, 2.0L, 2025 | $28,500 | $29,100 |
| Hyundai, 6cyl, 3.3L | $23,700 | $24,000 |
## 🚀 Quick Start
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Run Jupyter Notebook: `jupyter notebook FinalAssignment.ipynb`
4. Update `data/cars-2025.csv` if dataset changes

Requires Python 3.8+, pandas, scikit-learn, matplotlib, seaborn, numpy
## 📁 Project Structure
```
.
├── FinalAssignment.ipynb
├── README.md
├── data/
│   └── cars-2025.csv
├── results/
│   ├── corr_heatmap.png
│   ├── feature_importance.png
│   └── model_scores.csv
└── requirements.txt
```
## 🛠️ Future Improvements
- Try tree-based regressors (Random Forest, XGBoost)
- Add SHAP/LIME for explainability
- Containerize with Docker
- Build a Streamlit or Flask UI

Note: Update table values and add plot files as you generate them.
