# ML-Driven Credit Risk Optimization

## Project Overview
[cite_start]This project transforms credit risk management from traditional "risk avoidance" to "profit maximization"[cite: 19]. [cite_start]By leveraging advanced analytics, the model identifies high-value borrowers and surgically filters out toxic assets to increase portfolio profitability[cite: 3, 113].

[cite_start]*Disclaimer: Data used in this simulation is sourced from Kaggle for educational purposes and does not reflect actual company data[cite: 14].*

## Tech Stack
* [cite_start]**Language:** Python [cite: 247]
* [cite_start]**Algorithm:** Logistic Regression (Chosen for its explainability and probability scoring) 
* [cite_start]**Key Tasks:** EDA, Outlier Analysis, Probability Scoring, Financial Simulation [cite: 90, 252, 388, 469]

## Key Business Findings & Impact
[cite_start]Based on the simulation against a baseline default rate of 11.6%[cite: 103]:
* [cite_start]**Financial Uplift:** Projected Net Profit increase of +$87.6 Million/Year (+6.33%)[cite: 225].
* [cite_start]**Risk Reduction:** Default Rate successfully dropped to 9.71%, achieving the target of < 10% NPL[cite: 228, 229].
* [cite_start]**Optimal Threshold:** The mathematical "sweet spot" for approval was found at a 0.79 risk probability cut-off, maintaining a healthy approval rate of 94.85%[cite: 214, 575].

## Key Risk & Safety Drivers
* [cite_start]**Primary Risk:** Loan-to-Income Ratio (+0.47 coefficient) is the strongest predictor of default[cite: 144, 554]. [cite_start]High interest rates (+0.46) also correlate with higher default, confirming an adverse selection paradox[cite: 147, 556].
* [cite_start]**Primary Safety:** Age (-0.59) and Employment Tenure (-0.34) are the strongest indicators of financial discipline and repayment reliability[cite: 174, 177, 559, 560].
