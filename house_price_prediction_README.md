# 🏠 House Price Prediction with Multiple Linear Regression

This project uses the **Ames Housing dataset** to predict home sale prices using a **multiple linear regression model**. The goal is to apply data preprocessing, exploratory analysis, feature engineering, and modeling to accurately estimate property values based on various housing attributes.

---

## 📊 Dataset

The dataset comes from the Kaggle competition:  
👉 [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

It contains detailed records of residential home sales in Ames, Iowa, including variables like square footage, condition, number of bedrooms/bathrooms, garage capacity, and building type.

---

## ⚙️ Tools and Libraries

- **Python**
- **Pandas** – data loading and transformation  
- **Matplotlib** – visual exploration  
- **Scikit-learn** – model training, evaluation, and preprocessing  

---

## 📈 Project Workflow

1. **Data Exploration** – Analyzed distributions and trends in housing features and sale prices  
2. **Data Cleaning** – Removed irrelevant columns and handled missing values  
3. **Feature Engineering**  
   - Combined separate square footage fields into a `TotalSqFt` column  
   - Created a new `Age` column based on the year built  
4. **Categorical Encoding** – Used one-hot encoding on building types  
5. **Outlier Removal** – Excluded homes priced below \$50,000 and above \$500,000  
6. **Model Training** – Trained a **multiple linear regression model** using `scikit-learn`  
7. **Model Evaluation** – Evaluated performance using **RMSE** and **R²**  

---

## 🔍 Sample Prediction

You can make a prediction for a new house by providing values for all the input features used in the model. See the notebook for a full example.

---

## 📁 File Structure

- `HousingRegression.ipynb` – main Jupyter notebook with code and analysis  
- `house_price_prediction_README.md` – this file  

---

## 🚀 Getting Started

1. Clone the repository  
2. Install required libraries (via `requirements.txt` or manually)  
3. Run the notebook in Jupyter Lab or Jupyter Notebook  

```bash
pip install pandas matplotlib scikit-learn
