# Hello all,

I am a quantitative analyst/data scientist who builds and validates **credit risk and forecasting models**. Previously, I spent two years in economic research at the **Federal Reserve Bank of Boston**, building nowcasting and time-series models for monetary policy. Today I develop and validate probability-of-default and CECL models for banks.

I bring an understanding of both sides of modeling: building models, and knowing how they fail.

## Featured Projects

### [Credit Default Prediction Model](https://github.com/3JSaunders1/credit-default-model)
An end-to-end PD and expected loss framework on ~590K Lending Club loans, built and validated the way a bank would.
- Logistic regression, monotonic XGBoost, and a Weight of Evidence scorecard, with out-of-time validation
- Expected loss (PD × LGD × EAD) validated against realized losses
- Quarterly PSI and calibration monitoring, SHAP reason codes, and FRED macro features joined in SQL
- PySpark pipeline reconciled against SQL at 1M+ rows, with 42 automated tests in CI
- **Key finding:** concept drift that input monitoring alone missed, driving a 14% expected-loss shortfall

### [Macro-Driven Credit Risk Lab](https://github.com/3JSaunders1/macro-credit-risk-lab)
A stress-testing platform linking macroeconomic scenarios to credit losses, validated the way a model risk team would.
- Five forecasting models (VAR, Cholesky and sign-restricted SVARs, Bayesian VAR, and local projections), backtested out of sample against a random walk
- A dynamic credit loss model on 40 years of FRED charge-off data, validated with conditional backtests through 2008 and COVID
- A scenario engine propagating structural shocks through the Bayesian VAR into 9-quarter cumulative losses, compared against actual 2008 losses
- FastAPI service, interactive Streamlit dashboard, and 64 automated tests in CI
- **Key finding:** reviewing the platform like a validator, I found and corrected eight model errors; the loss model captured only two-thirds of 2008 losses, showing why severe scenarios need overlays

## Tools & Methods

**Languages and tools:** Python · SQL · PySpark · R · MATLAB · Git · GitHub Actions
**Modeling:** logistic regression · gradient boosting · WoE scorecards · expected loss · time-series econometrics · calibration and drift monitoring · explainability

## Connect

[LinkedIn](https://www.linkedin.com/in/john-saunders-03a650260/)
