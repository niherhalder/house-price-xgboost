# 🏠 House Price Prediction using XGBoost

This project builds a robust regression pipeline using XGBoost to predict house sale prices based on 80+ features such as neighborhood, quality, area, and more. It includes detailed EDA, feature engineering, hyperparameter tuning, and model evaluation.

---

## Project Structure 📁

```
house-price-xgboost/
├── notebooks/
├── gallery/
├── model/
│   └── xgb_final_model.pkl
├── submission/
│   └── blended_submission.csv
├── report/
│   └── project_summary.pdf
├── requirements.txt
├── README.md
```

---

## Tools & Libraries Used 📊

- `XGBoost` — Gradient boosting model
- `Pandas`, `NumPy` — Data handling
- `Matplotlib`, `Seaborn`, `Plotly` — Visualizations
- `Scikit-learn` — Cross-validation, preprocessing, metrics

---

## Dataset 🏘️

- **Source:** Kaggle – [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- ~1,460 residential property records
- 80+ engineered features (numeric & categorical)

---

## Model Performance ✅

- **Model Used:** Tuned XGBoost Regressor  
- **CV RMSE (log-space):** `0.1229`  
- **Real RMSE:** `~0.13`  
- **Kaggle Public Leaderboard Score:** `0.12826`

---

## Gallery Highlights (Visuals) 📈

Visuals available in the `gallery/` folder:
- `houseprice.png` — Target variable distribution  
- `featureImportance.png` — Top features from XGBoost  
- `histogram.png`, `missingvalueBarplot.png`, `missingvalueCmap.png` — EDA insights  
- `featureDecisionTable.png` — Feature selection summary  
- `salepricebyOverquality.png`, `correlatedfeaturesSaleprice.png`, `scatterPlot.png` — Key relationships

---

## How to Run the Project 🚀

### 1. Clone the Repository

```bash
git clone https://github.com/niherhalder/house-price-xgboost.git
cd house-price-xgboost
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Jupyter Notebooks

```bash
jupyter notebook
```

> Open and execute the notebooks sequentially from `01` to `06` inside the `notebooks/` folder.

---

## Deliverables 📂

- ✅ Clean 6-part notebook pipeline in [`notebooks/`](notebooks/)
- 🖼️ Gallery of 9 key visualizations in [`gallery/`](gallery/)
- 🧠 Trained XGBoost model: [`model/xgb_final_model.pkl`](model/xgb_final_model.pkl)
- 📊 Correct submission file: [`submission/blended_submission.csv`](submission/blended_submission.csv)
- 📄 PDF report summary: [`report/project_summary.pdf`](report/project_summary.pdf)
- 📘 Full documentation, structure, and code-ready environment

---

## Conclusion 🎯

✅ Built a complete regression pipeline to predict house prices  
📊 Leveraged EDA, feature engineering, and XGBoost tuning  
💡 Identified key drivers like `OverallQual`, `GrLivArea`, and `GarageCars`  
🧠 Model generalizes well for pricing, analytics, and investment tools  
📂 Deliverables include full pipeline, prediction output, visuals, and summary report

---

📢 **[⭐ Star the repository](https://github.com/niherhalder/house-price-xgboost) if you find it useful or inspiring!**