T1_JPM_Forage (1).ipynb
Quantitative Research – Commodities

Task 1: Natural Gas Price Extrapolation

Uses historical + forward prices (monthly snapshots).

Fits regression with trend + seasonality (Fourier terms).

Provides estimate_price(date) to predict prices for any date (+1 year extrapolation).

Generates daily/monthly curves and diagnostics.

Task 2: Storage Contract Valuation

Implements price_storage_contract() to simulate gas injections/withdrawals under rate, capacity, and cost constraints.

Computes contract value (P&L), ending inventory, and unsatisfied orders.

Includes examples of summer-to-winter storage arbitrage.

Credit Risk JPM.ipynb
Retail Banking – Credit Risk

Builds a predictive model for loan defaults (PD – probability of default).

Uses customer data to train a logistic regression with preprocessing pipeline.

Evaluates model with ROC-AUC, PR-AUC, Brier score, calibration plots.

Converts PD into Expected Loss (EL) using LGD × EAD × PD.

Produces loan-level and portfolio-level loss estimates.

JPM_FICO_Bucket.ipynb
Credit Risk – Score Segmentation

Groups loans by FICO score buckets.

Analyzes default rates across score ranges.

Provides insights for risk-based pricing and portfolio monitoring.
