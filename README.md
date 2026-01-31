# How Governance Quality and Economic Freedom Affect GDP Growth  
### A Cross-Country Econometric and Machine Learning Study

---

## Introduction

This project presents a **cross-country empirical analysis** examining how governance
quality and economic freedom influence GDP growth across 186 countries.

Using a rigorously validated **OLS econometric framework with robust standard errors**
and cross-checked with **machine learning models**, the study isolates the most
significant drivers of economic growth. The findings show that **labor market
conditions (unemployment)**, **governance quality (government integrity)**, and
**inflation dynamics** are far more influential for GDP growth than aggregate economic
freedom scores.

The results challenge common policy assumptions and provide **data-driven guidance
for governments and international institutions**.

---

## Business & Policy Problem

Economic growth remains the central objective of governments worldwide. While
traditional growth models emphasize capital, labor, and technology, policymakers
increasingly recognize that **institutions and governance quality** play a decisive
role.

**Key policy question:**

> Do higher economic freedom and better governance measurably improve GDP growth, and
> which specific institutional factors matter the most?

This question is critical for:
- Governments and policymakers  
- International organizations  
- Economic analysts and consultants  
- Development and public policy teams  

---

## Research Objectives

- Quantify the impact of **economic freedom** on GDP growth  
- Isolate the role of **governance quality**, particularly corruption and integrity  
- Compare institutional variables with **macroeconomic controls**  
- Validate econometric findings using **machine learning models**  

---

## Data Description

- **Dataset:** Cross-country economic indicators  
- **Observations:** 186 countries  
- **Source:** Economic Freedom Index and macroeconomic databases  

### Key Variables

**Dependent Variable**
- GDP Growth Rate (%)

**Independent Variables**
- Overall Economic Freedom Score  
- Property Rights  
- Government Integrity (corruption proxy)  
- Fiscal Health  
- Trade Freedom  
- Unemployment Rate (%)  
- Inflation Rate (%)  
- Public Debt (% of GDP)

---

## Methodology

### Econometric Framework

- **Primary Model:** Multiple Linear Regression (OLS)  
- **Correction:** HC3 Robust Standard Errors (heteroscedasticity detected via
  Breusch–Pagan test)  
- **Evaluation Metrics:** Coefficient significance, adjusted R²

- <img width="818" height="704" alt="Image" src="https://github.com/user-attachments/assets/be2dd505-d112-44b4-8ffe-bd1160ee5a42" />

### Data Preparation

- Missing value treatment using **mean and median imputation** based on distribution  
- Data type standardization and variable renaming  
- Outlier handling via **Winsorization and IQR-based correction**  
- Final dataset contained **zero missing values**  

---

## Key Econometric Results

The OLS model identifies **three statistically significant drivers of GDP growth**:

### Core Findings

- **Unemployment Rate**  
  Strong negative effect on GDP growth  
  → Higher unemployment significantly reduces economic growth  

- **Government Integrity (Governance Quality)**  
  Strong positive effect on growth  
  → Lower corruption is associated with faster economic growth  

- **Inflation Rate**  
  Positive and significant relationship  
  → Mild inflation is linked with higher nominal GDP growth  

### Insignificant Variables

- Overall Economic Freedom Score  
- Property Rights  
- Trade Freedom  
- Public Debt  

**Key insight:**  
Broad economic freedom indices are less informative than **specific governance and
labor market indicators**.

---

## Robustness & Validation

To ensure reliability, the findings were validated using multiple approaches:

### Sensitivity Analysis
- Drop-one-variable tests confirmed stability of key coefficients  

### Alternative Specification
- Log-transformed GDP growth model produced consistent results  

### Machine Learning Validation
- Ridge, Lasso, and ElasticNet confirmed model stability  
- Random Forest and Gradient Boosting ranked:
  - Unemployment
  - Inflation
  - Government Integrity  
  as the most important predictors  

This cross-validation confirms that the results are **not model-specific artifacts**.

---

## Policy Implications

Based on robust empirical evidence, the study suggests:

- **Labor market stability is the highest growth priority**  
  Job creation policies yield strong growth dividends  

- **Anti-corruption and governance reforms matter more than aggregate freedom scores**  
  Institutional quality directly supports economic performance  

- **Macroeconomic stability remains essential**  
  Inflation should be managed carefully to support growth without instability  

---

## Key Takeaway

> Economic growth is driven less by broad economic freedom indices and more by **clean
> governance, employment conditions, and macroeconomic stability**.

This insight is critical for designing **targeted, effective growth policies**.

---

## My Role & Contributions

- Cross-country data cleaning and preparation  
- Econometric model design and estimation  
- Robustness testing and diagnostics  
- Machine learning benchmarking  
- Policy interpretation and recommendations  
- End-to-end conversion of raw data into actionable insights  

---

## Skills Demonstrated

- Econometrics (OLS, robust inference)  
- Cross-country data analysis  
- Policy evaluation  
- Machine learning validation  
- Data cleaning & preprocessing  
- Economic research and business storytelling  
