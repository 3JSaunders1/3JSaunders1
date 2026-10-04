# Hello all, 👋

I am a quantitative analyst/data scientist who builds and validates **credit risk and forecasting models**. Previously, I spent two years in economic research at the **Federal Reserve Bank of Boston**, building nowcasting and time-series models for monetary policy. Today I develop and validate probability-of-default and CECL models for banks.

What I bring is both sides of modeling: building models, and knowing how they fail.

## 🔍 Featured Projects

### [Credit Default Prediction Model](https://github.com/3JSaunders1/credit-default-model)
An end-to-end PD and expected loss framework on ~590K Lending Club loans, built and validated the way a bank would.
- Logistic regression, monotonic XGBoost, and a Weight of Evidence scorecard, with out-of-time validation
- Expected loss (PD × LGD × EAD) validated against realized losses
- Quarterly PSI and calibration monitoring, SHAP reason codes, and FRED macro features joined in SQL
- PySpark pipeline reconciled against SQL at 1M+ rows, with 42 automated tests in CI
- **Key finding:** concept drift that input monitoring alone missed, driving a 14% expected-loss shortfall

### [Macro-Driven Credit Risk Lab](https://github.com/3JSaunders1/macro-credit-risk-lab)
A stress-testing platform linking macroeconomic forecasts to default risk.
- Five interchangeable forecasting models: VAR, Cholesky and sign-restricted SVARs, Bayesian VAR, and local projections
- Probability-of-default scoring under baseline and stress scenarios
- FastAPI service, interactive Streamlit dashboard, and automated tests

## 🛠️ Tools & Methods

**Languages and tools:** Python · SQL · PySpark · R · MATLAB · Git · GitHub Actions
**Modeling:** logistic regression · gradient boosting · WoE scorecards · expected loss · time-series econometrics · calibration and drift monitoring · explainability

## 📫 Connect

[LinkedIn](https://www.linkedin.com/in/john-saunders-03a650260/)
