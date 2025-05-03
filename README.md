# 🏡 House Prices Prediction - Ridge & Lasso Regression

This project applies **Ridge and Lasso Regression** to predict **house prices** based on various features.

## 📊 Dataset
- Dataset: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- Download `train.csv` and `test.csv`, then place them in the project folder.

## 🚀 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/inaya-r/housing-prices-regression.git
   cd housing-prices-regression
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
   Open `housing_analysis.ipynb` in Jupyter.

## 📈 Models Used
- **OLS Regression** (Baseline)
- **Ridge Regression** (Handles multicollinearity)
- **Lasso Regression** (Feature selection)

## 📌 Evaluation Metrics
- **RMSE (Root Mean Squared Error)** | Measures how far predictions are from actual prices, penalizing large errors more. |
- **MAE (Mean Absolute Error)** | Measures average absolute prediction error.
- **R² (R-Squared)** | Indicates how much variance in `SalePrice` is explained by the features. 

## 📌 Key Findings
✅ Ridge Regression helped with overfitting.  
✅ Lasso Regression identified the most important features.  
✅ Random Forests (parameters optimized with a basic grid search) gave lowest RMSE.

## 📩 Contact & Contributions
For suggestions or improvements, feel free to **open an issue** or **submit a pull request**! 🚀

