
# Quantitative Economics Portfolio
**Wyatt Whiting** | Political Science, BYU-Idaho

This repository contains quantitative economics projects demonstrating skills in:
- Econometric analysis (OLS regression, panel data, interaction models)
- Economic data acquisition and wrangling (FRED API, World Bank WDI, Penn World Tables)
- Statistical programming (Python, R)
- Data visualization for policy research

---

## Projects

### 1. [Cross-National Inequality & Development Analysis](./inequality-development-analysis/)
**File:** `Correct_Term-Project-Cleaned.Rmd`

Regression analysis examining how economic inequality affects development outcomes (life expectancy, GNI per capita, education) across 60+ countries using panel data from 2000-2020.

**Methods:**
- OLS regression with interaction terms to test regime-specific effects
- AR(1) autoregressive model for inequality persistence analysis
- Model diagnostics (residual plots, Q-Q plots, homoscedasticity tests)

**Data Sources:** World Bank World Development Indicators, V-Dem Institute

**Key Skills:** R programming, ggplot2 visualization, panel data construction, interaction modeling

---

### 2. [GDP Measurement & Welfare Analysis](./gdp-welfare-analysis/)
**File:** `should_do_ch2.qmd`

Cross-country empirical analysis testing relationships between GDP per capita and welfare indicators (life expectancy, unemployment, inequality).

**Methods:**
- API-based data acquisition from FRED and World Bank WDI
- Correlation analysis with scatter plot visualization
- Time-series decomposition of U.S. GDP expenditure components (1960-present)

**Key Findings:** Moderate positive correlation between GDP and life expectancy (r=0.676); weak correlations with unemployment and Gini coefficient, demonstrating GDP's limitations as welfare proxy.

**Key Skills:** Python (pandas, matplotlib), API integration, cross-sectional data analysis

---

### 3. [International Growth Rate Analysis](./growth-analysis/)
**File:** `should_do_ch3.qmd`

Comparative analysis of economic growth patterns across six countries (USA, China, South Africa, Bangladesh, DRC, Ghana) from 1990-2010 using Penn World Tables data.

**Methods:**
- Year-over-year growth rate calculations with log transformations
- Summary statistics: average growth, volatility (standard deviation), negative growth frequency
- Ratio-scale visualization for growth comparisons

**Key Skills:** Panel data organization, growth accounting, time-series analysis, FRED API

---

### 4. [Development Accounting: Physical vs. Human Capital](./development-accounting/)
**File:** `should_do_ch4.qmd`

Implementation of Cobb-Douglas and Hall-Jones development accounting frameworks to decompose cross-country income differences into physical capital, human capital, and total factor productivity (TFP).

**Methods:**
- Calculated implied TFP for 60+ countries using production function approach
- Compared model fit (R²) between baseline Cobb-Douglas and Hall-Jones specifications
- Evaluated contribution of capital vs. human capital vs. TFP to income gaps

**Key Skills:** Production function estimation, model comparison, cross-country decomposition

---

### 5. [Solow Growth Model: Policy Simulations](./solow-simulations/)
**File:** `should_do_ch5.qmd`

Numerical simulations of the Solow growth model to analyze policy interventions (savings rate changes, TFP shocks, capital transfers).

**Methods:**
- Built discrete-time simulation with convergence algorithm (while-loop with tolerance)
- Conducted controlled experiments: savings rate reduction, TFP increase, foreign aid scenarios
- Analyzed transition dynamics and steady-state comparative statics

**Key Findings:** TFP increases produce permanent welfare gains (+83.7% long-run consumption for 50% TFP increase), while capital transfers yield only temporary effects (+25.99% impact, zero long-run change).

**Key Skills:** Python simulation modeling, economic theory implementation, policy experiment design

---

## Technical Skills Demonstrated
- **Languages:** Python, R
- **Libraries:** pandas, matplotlib, numpy, ggplot2, dplyr, broom
- **Data Sources:** FRED API, World Bank WDI, Penn World Tables, V-Dem
- **Methods:** OLS regression, panel data, interaction models, time-series analysis, simulation modeling
