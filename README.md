# ML-Driven Credit Risk Optimization

## Project Overview
This project transforms credit risk management from traditional "risk avoidance" to "profit maximization". By leveraging advanced analytics, the model identifies high-value borrowers and surgically filters out toxic assets to increase portfolio profitability.

*Disclaimer: Data used in this simulation is sourced from Kaggle for educational purposes and does not reflect actual company data.*

## Tech Stack
* **Language:** Python
* **Algorithm:** Logistic Regression (Chosen for its explainability and probability scoring)
* **Key Tasks:** EDA, Outlier Analysis, Probability Scoring, Financial Simulation

## Key Business Findings & Impact
Based on the simulation against a baseline default rate of 11.6%:
* **Financial Uplift:** Projected Net Profit increase of +$87.6 Million/Year (+6.33%).
* **Risk Reduction:** Default Rate successfully dropped to 9.71%, achieving the target of < 10% NPL.
* **Optimal Threshold:** The mathematical "sweet spot" for approval was found at a 0.79 risk probability cut-off, maintaining a healthy approval rate of 94.85%.

## Key Risk & Safety Drivers
* **Primary Risk:** Loan-to-Income Ratio (+0.47 coefficient) is the strongest predictor of default. High interest rates (+0.46) also correlate with higher default, confirming an adverse selection paradox.
* **Primary Safety:** Age (-0.59) and Employment Tenure (-0.34) are the strongest indicators of financial discipline and repayment reliability.
