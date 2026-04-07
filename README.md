# SEB SME Cash Flow Classifier

An ML prototype developed for SEB Banka in collaboration with
the RTU HPC Programme to classify and predict SME behavior
based on cash flow patterns, processing approximately 20 million
transactions on high-performance computing infrastructure.

## Programme
RTU HPC Programme: Creating Innovative Digital Solutions
for HPC Challenges — SEB Banka. 2025.

## Overview
- Processed approximately **20 million transactions** from
  SEB Banka on RTU HPC infrastructure
- Classified **1,000+ SMEs** into 5 cash flow pattern types:
  Stable, Lumpy, Negative, Steady Growth, Seasonal
- Forecasted 12-month future cash flow using Prophet
- Evaluated 5 ML models on HPC infrastructure
- Delivered an interactive Figma dashboard for stakeholders

## Dashboard Prototype
Interactive Figma dashboard built for SEB stakeholders:
[View Dashboard →](https://www.figma.com/proto/Btuixb8JuKpGQovtThLrJS/SEB_Dashboard?node-id=38-73)


## Model Performance

| Model                | Train Accuracy | Test Accuracy |
|----------------------|---------------|---------------|
| XGBoost              | 100%          | 98.0%         |
| Random Forest        | 100%          | 98.0%         |
| Neural Network (MLP) | 82.5%         | 78.5%         |
| Logistic Regression  | 66.3%         | 66.0%         |
| SVM                  | 62.4%         | 62.0%         |

Tree-based models (XGBoost, Random Forest) significantly
outperformed linear models on this structured financial dataset.

## Tech Stack
Python · XGBoost · Random Forest · Prophet ·
Scikit-learn · Pandas · Matplotlib · Seaborn · HPC

## Files
- `SEB_HPC_PROJECT.ipynb` — Full notebook (EDA,
  classification, forecasting, model evaluation)
- `cash_flow_steady_growth.html` — Interactive
  visualization for Steady Growth pattern
