# Customer Lifetime Value (LTV) Prediction

This repository contains a case study on predicting **Customer Lifetime Value (LTV)** for a digital wallet company. The goal is to analyze user behavior, engineer features, and build predictive models that estimate future customer value.

## Repository Contents

- **`LTV_Prediction_Python_CaseStud.ipynb`**  
  Jupyter notebook with data exploration, feature engineering, and modeling steps.

- **`digital_wallet_ltv_dataset.csv`**  
  Dataset containing anonymized transaction and behavior data for digital wallet users.

## Dataset Description

The dataset includes the following fields (sample overview):

- `customer_id` – unique customer identifier  
- `signup_date` – date the customer registered  
- `last_transaction_date` – most recent transaction date  
- `total_transactions` – total number of transactions  
- `total_spent` – cumulative amount spent  
- `avg_transaction_value` – average spend per transaction  
- `wallet_balance` – balance left in the wallet  
- `is_active` – whether the customer is currently active  

*(Adjust column descriptions if your dataset has additional fields.)*

## Objectives

1. Explore customer behavior using descriptive statistics and visualization.  
2. Engineer features that capture retention, activity, and spending patterns.  
3. Build machine learning models to predict LTV.  
4. Evaluate performance using standard regression metrics.

## Getting Started

### Prerequisites

- Python 3.8+  
- Jupyter Notebook  
- Libraries:
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  

Install dependencies with:

```bash
pip install -r requirements.txt

## Run the Notebook

Clone this repository:

```bash
git clone https://github.com/your-username/ltv-prediction.git
cd ltv-prediction


Start Jupyter Notebook:

jupyter notebook


Open LTV_Prediction_Python_CaseStud.ipynb and run all cells.

Results:

EDA reveals insights into customer activity and spend.

Predictive models estimate customer lifetime value with measurable accuracy.

Results can be used to guide retention and marketing strategies.
