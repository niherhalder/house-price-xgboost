# 🏠 House Price Prediction using XGBoost

This project builds a robust regression pipeline using XGBoost to predict house sale prices based on 80+ features such as neighborhood, quality, area, and more. It includes detailed EDA, feature engineering, hyperparameter tuning, and model evaluation.

---

## 📁 Project Structure
house-price-xgboost/
├── notebooks/
│ ├── 01_eda_and_visualization-checkpoint.ipynb
│ ├── 02_data_cleaning-checkpoint.ipynb
│ ├── 03_baseline_model-checkpoint.ipynb
│ ├── 04_model_training-checkpoint.ipynb
│ ├── 05_evaluation_and_tuning-checkpoint.ipynb
│ └── 06_visualization_and_submission-checkpoint.ipynb
├── gallery/
│ ├── houseprice.png
│ ├── featureImportance.png
│ ├── histogram.png
│ ├── missingvalueBarplot.png
│ ├── missingvalueCmap.png
│ ├── featureDecisionTable.png
│ ├── salepricebyOverquality.png
│ ├── correlatedfeaturesSaleprice.png
│ └── scatterPlot.png
├── model/
│ └── xgb_model.pkl
├── submission/
│ └── final_submission.csv
├── report/
│ └── House_Price_Project_Summary.pdf
├── requirements.txt
├── .gitignore
└── README.md

yaml
Copy
Edit

---

## 📊 Tools & Libraries Used

- `XGBoost` — Gradient boosting model
- `Pandas`, `NumPy` — Data handling
- `Matplotlib`, `Seaborn`, `Plotly` — Visualizations
- `Scikit-learn` — Cross-validation, preprocessing, metrics

---

## 🏘️ Dataset

- **Source**: Kaggle – [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- ~1,460 residential property records
- 80+ engineered features (numeric & categorical)

---

## ✅ Model Performance

- **Model Used**: Tuned XGBoost Regressor  
- **CV RMSE (log-space)**: `0.1229`  
- **Real RMSE**: `~0.13`  
- **Kaggle Public Leaderboard Score**: `0.12826`

---

## 📈 Gallery Highlights (Visuals)

Here are some visualizations and insights included in the `gallery/` folder:

- 📊 `houseprice.png` — Distribution of target variable
- 📉 `featureImportance.png` — Top features from XGBoost
- 📊 `histogram.png` — Overall numeric feature distributions
- 🔍 `missingvalueBarplot.png` — Missing value bar overview
- 🧊 `missingvalueCmap.png` — Heatmap of missing features
- 📋 `featureDecisionTable.png` — Feature selection summary
- 💡 `salepricebyOverquality.png` — SalePrice vs. OverallQual
- 🔗 `correlatedfeaturesSaleprice.png` — Correlation heatmap
- 📌 `scatterPlot.png` — Area vs. Price relationship

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/house-price-xgboost.git
cd house-price-xgboost
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run Jupyter Notebooks
Navigate to the notebooks/ folder and open notebooks in order (01 → 06):

bash
Copy
Edit
jupyter notebook
📂 Deliverables
Clean 6-part notebook pipeline

Gallery of 9 key visualizations

Trained XGBoost model (.pkl)

Submission file (.csv)

PDF summary report

Full documentation and metrics

✅ Conclusion
✅ Successfully built a regression pipeline to predict house prices using XGBoost
📊 Leveraged data preprocessing, EDA, and model tuning for performance
💡 Achieved high model accuracy with insights from key features like OverallQual, GrLivArea, and GarageCars
🧠 Model generalizes well and is ready for use in pricing strategies, real estate analytics, and investment tools
📂 Deliverables include: Clean code, trained model, predictions file, and summary report