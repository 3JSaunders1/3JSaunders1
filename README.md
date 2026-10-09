# Hi, I'm John 👋

**Quantitative analyst and data scientist** building and validating credit risk and macroeconomic models.

- Currently developing challenger credit risk models and validating banks' CECL models at a public accounting firm
- Previously a Senior Research Associate at the **Federal Reserve Bank of Boston**, building forecasting and nowcasting models for monetary policy

I care about models that hold up out of sample: validated against benchmarks, monitored for drift, and engineered to be reproducible.

---

## Projects

### 🔗 [Credit Risk Platform](https://github.com/3JSaunders1/credit-risk-platform)
An integrated stress-testing platform linking my two projects below: macroeconomic scenarios flow through loan-level PDs into portfolio expected losses (PD × LGD × EAD).
- Stressed losses for a **$3.62B, 283,000-loan portfolio**, from $238.6M at baseline to $322.2M under a severe recession
- **Data contracts** and **enforced temporal integrity** (no look-ahead), validated end to end
- The portfolio's actual 2015 loss lands almost exactly on the Adverse scenario
- Streamlit dashboard, Docker, 18 tests in CI

### 📉 [Credit Default Prediction Model](https://github.com/3JSaunders1/credit-default-model)
A bank-style probability of default and expected loss model on ~590,000 Lending Club loans.
- Logistic regression, XGBoost, monotonic XGBoost, and a WoE scorecard, validated **out of time**
- Found **concept drift that input monitoring missed:** stable inputs (PSI 0.001), failing calibration
- Expected loss validated against **$274M of realized losses**, with the gap traced to default frequency
- SQL and PySpark pipelines reconciled across 1M+ loans, Docker, logging, 49 tests in CI

### 🌐 [Macro-Driven Credit Risk Lab](https://github.com/3JSaunders1/macro-credit-risk-lab)
A macro stress-testing platform: five forecasting models feeding a dynamic credit loss model.
- VAR, Cholesky and sign-restricted SVARs, a Minnesota-prior **Bayesian VAR**, and local projections
- Backtested out of sample against a random walk, with Diebold-Mariano tests
- Dynamic loss model validated through **2008 and COVID**; eight model errors found and corrected in review
- FastAPI service, Streamlit dashboard, Docker Compose, 67 tests in CI

---

## Tools

**Languages and data:** Python · SQL · R · PySpark · DuckDB · pandas · NumPy
**Modeling:** scikit-learn · XGBoost · statsmodels · SciPy · SHAP
**Engineering:** Docker · FastAPI · Streamlit · pytest · GitHub Actions · Make · Git

---

📫 Reach me on [LinkedIn][(https://www.linkedin.com/in/john-saunders-03a650260/)]
