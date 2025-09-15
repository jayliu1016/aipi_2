# Telco Customer Churn — Interpretable Models (Logistic & GAM)

**Colab notebook:**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/jayliu1016/aipi_2/blob/main/notebooks/telco_churn_models.ipynb)

## Dataset
IBM Telco Customer Churn (Kaggle): WA_Fn-UseC_-Telco-Customer-Churn.csv.  
Each row is a customer; target **Churn**; key features include **tenure**, **MonthlyCharges**, **contract**, **payment method**, and support add-ons.

## How to run
1. Open the Colab notebook via the badge above.  
2. Run the first cell to install dependencies.  
3. The dataset is already in `data/` in this repo; the notebook reads it directly.  
4. Execute cells top-to-bottom: EDA → OLS → Logistic → GAM → Comparison.

## Repo structure
.
├── data/              # dataset lives here
├── notebooks/         # Colab .ipynb
├── README.md
└── requirements.txt   # versions for local reproducibility
