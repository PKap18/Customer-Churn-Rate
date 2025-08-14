# Customer Churn Analysis

An original, end-to-end analytics project with **synthetic data** generated on 2025-08-14 (UTC).  
This ensures the project is unique and not copied from any public source.

## Project Structure
```
customer_churn/
├── customer_churn_analysis.ipynb  # or analysis.py if notebook unsupported
├── data/
│   └── churn_data.csv
├── README.md
└── requirements.txt
```

## Highlights
- Clean, realistic **synthetic dataset** (~8,000 rows, 17 columns)
- **EDA**: churn rates by contract, tenure effects, charges distribution
- **Modeling**: Logistic Regression and Random Forest
- **Evaluation**: Accuracy, Precision, Recall, F1, ROC AUC
- **Explainability**: Coefficients & feature importances
- **Plots**: Matplotlib-only (no seaborn)

## How to Run
```bash
pip install -r requirements.txt
jupyter lab  # or jupyter notebook
# open customer_churn_analysis.ipynb and run all cells
```
