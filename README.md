# 🏠 House Price Prediction using XGBoost

This project builds a robust regression pipeline using XGBoost to predict house sale prices based on 80+ features such as neighborhood, quality, area, and more. It includes detailed EDA, feature engineering, hyperparameter tuning, and model evaluation.

---

## 📁 Project Structure

house-price-xgboost/
├── notebooks/
├── gallery/
├── model/
├── submission/
│ └── blended_submission.csv
├── report/
├── requirements.txt
├── README.md

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

- `houseprice.png` — Target variable distribution  
- `featureImportance.png` — Top features via XGBoost  
- `histogram.png`, `missingvalueBarplot.png`, `missingvalueCmap.png`  
- `featureDecisionTable.png` — Feature selection logic  
- `salepricebyOverquality.png`, `correlatedfeaturesSaleprice.png`, `scatterPlot.png`

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/niherhalder/house-price-xgboost.git
cd house-price-xgboost
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run Jupyter Notebooks
bash
Copy
Edit
jupyter notebook
Open and execute notebooks in order (01 to 06)

📂 Deliverables
Clean 6-part notebook pipeline

Gallery of 9 key visualizations

Trained XGBoost model (xgb_model.pkl)

Correct Submission: blended_submission.csv

PDF report summary

Full documentation

✅ Conclusion
✅ Built a complete regression pipeline to predict house prices
📊 Leveraged EDA, feature engineering, and XGBoost tuning
💡 Identified key features like OverallQual, GrLivArea, and GarageCars
🧠 Generalizes well for pricing, analytics, and investment insights
📂 Deliverables include notebook pipeline, predictions, visuals, and results

