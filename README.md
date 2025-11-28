# 📈 Ghana Inflation Prediction using Machine Learning

## 🌟 Project Overview
This project predicts Ghana's inflation rates for 2026-2030 using historical economic data and machine learning. The model helps policymakers and economists forecast economic trends.

## 🎯 Business Problem
Ghana faces significant inflation fluctuations that impact economic stability. This project provides data-driven forecasts to support better decision-making.

## 📊 Project Files

### `Predicted_Inflation_for_2026_2030.ipynb`
**Notebook Overview**
End-to-end machine learning project predicting Ghana's inflation rates using XGBoost and economic indicators.

**Project Structure**
1. **Data Loading & Exploration** - Understanding the dataset
2. **Data Preprocessing** - Handling missing values and feature engineering
3. **Model Development** - XGBoost implementation with hyperparameter tuning
4. **Model Validation** - Cross-validation and performance evaluation
5. **Future Predictions** - Inflation forecasts for 2026-2030
6. **Visualization** - Charts and graphs for insights

**Key Features**
- Complete ML pipeline from data cleaning to deployment
- 10-fold cross-validation for robust model evaluation
- Feature importance analysis
- Interactive visualizations
- 5-year inflation forecasts

### `Ghana Economic Data1.csv`
**Dataset Overview**
Historical economic indicators for Ghana from 1990 to 2025, containing key macroeconomic variables used for inflation prediction modeling.

**Columns Description**
- **Year**: Calendar year (1990-2025)
- **GDP Per Capita (Current US$)**: Economic output per person
- **GDP (Current US$)**: Total economic output
- **Inflation Consumer Prices (Annual %)**: Target variable - annual inflation rate
- **Inflation GDP Deflator (Annual %)**: Alternative inflation measure
- **Consumer Price Index (CPI)**: Price level index for goods and services
- **Exchange Rate**: Local currency units per US dollar

**Source**: World Bank Open Data & Ghana Statistical Service

## Technical Stack
- Python, Pandas, NumPy
- XGBoost, Scikit-learn
- Matplotlib
- Jupyter Notebook


## 🚀 Installation & Usage
```bash
# Clone repository
git clone  https://github.com/TechDiva001/inflation-price-prediction-project.git 

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook Predicted_Inflation_for_2026_2030.ipynb
