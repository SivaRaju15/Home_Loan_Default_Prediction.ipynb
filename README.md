# PRCP-1006 Home Loan Default Prediction

## Project Overview
This is my capstone project for Data Science.  
A bank wants to reduce losses from customers who default on home loans.  
I built a complete end-to-end solution that analyses customer data and predicts whether a new customer is **safe to give a loan** (TARGET = 0) or likely to default (TARGET = 1).

**Business Goal:** Help the bank approve loans only for low-risk customers.

## Dataset
- 7 CSV files from Home Credit Default Risk dataset  
- Total rows: 307,511 customers  
- Features include application data, previous loans, credit bureau history, POS cash, installments, and credit card information
- ## Dataset & Project Files

The complete dataset and project files are hosted on Google Drive:

- Dataset & project: [Download here](https://drive.google.com/file/d/1YWK3UE930-g5HNImuCRKyFx0t9MkoOKP/view?usp=drive_link)

Make sure the link is set to **“Anyone with the link” – Viewer** so others can open it without sign‑in issues. [web:31][web:34]

## What I Did (Step-by-Step)
1. Loaded and merged all 7 files efficiently  
2. Performed Exploratory Data Analysis (EDA) with clear visualizations  
3. Created new meaningful features (feature engineering)  
4. Cleaned data and handled missing values  
5. Built a strong machine learning model using LightGBM  
6. Evaluated the model with ROC-AUC score  
7. Explained the model using SHAP values  
8. Gave practical business recommendations

## Results
- **ROC-AUC Score:** 0.78+ (Good performance for this dataset)  
- The model can now predict default risk accurately  
- Top risk factors identified: high loan-to-income ratio, young age, and past defaults

## Technologies Used
- Python, Pandas, NumPy  
- Matplotlib & Seaborn (for visualizations)  
- Scikit-learn, LightGBM  
- SHAP (for model explainability)

## How to Run the Project
1. Download the dataset (7 CSV files)  
2. Open `Home_Loan_Default_Prediction.ipynb` in Jupyter Notebook  
3. Run all cells (first time merging takes 4-7 minutes)  
4. Check the final AUC score and plots

## Files in this Repository
- `Home_Loan_Default_Prediction.ipynb` → Complete notebook  
- `merged_home_loan_data.pkl` → Pre-merged data (fast loading)  
- `README.md` → This file

## Future Improvements
- Deploy as a web app using Streamlit  
- Try advanced models like XGBoost or CatBoost  
- Add more customer segmentation

**Made by:** Sivarala Yella Raju (B.Tech CSE 2025)  
Feel free to connect on LinkedIn for any questions!
