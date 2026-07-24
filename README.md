# country-size-income-per-capita-regression
Multiple linear regression analysis of the relationship between country size and GDP per capita using macroeconomic data from Our World in Data.

# The Relationship Between Country Size and Income per Capita

## Overview

This project analyzes the relationship between country size and income per capita using a multiple linear regression model. The analysis is based on macroeconomic indicators obtained from the **Our World in Data** database for the year **2019**.

The objective is to identify how structural variables such as population, urbanization, and life expectancy are associated with differences in GDP per capita across countries.

---

## Data Source

- Our World in Data
- World Bank Development Indicators

---

## Variables

### Dependent Variable
- **Log(GDP per capita)**

### Independent Variables
- Log(Population)
- Urban Population (% of total population)
- Life Expectancy at Birth

---

## Econometric Model

The model estimated is:

\[
\ln(GDPpc)=\beta_0+\beta_1\ln(Population)+\beta_2Urban+\beta_3LifeExp+\varepsilon
\]

The model was estimated using **Ordinary Least Squares (OLS)**.

---

## Methodology

The project includes:

- Data cleaning
- Data merging
- Logarithmic transformations
- Correlation analysis
- Scatter plots
- Multiple Linear Regression
- Residual Analysis
- Actual vs Predicted comparison

---

## Results

The regression model achieved an R² of approximately **0.78**, indicating that the selected explanatory variables account for a substantial proportion of the variation in GDP per capita across countries.

Main findings:

- Population shows a negative association with GDP per capita.
- Urbanization has a positive relationship with GDP per capita.
- Life expectancy is positively associated with GDP per capita.

These results should be interpreted as statistical associations rather than causal effects.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels

---

## Repository Structure

```
├── data/
├── notebooks/
├── figures/
├── report/
├── README.md
```

---

## References

- Our World in Data
- World Bank
- Wooldridge, J. M. (2013). *Introductory Econometrics: A Modern Approach.*






## Key Skills 

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Multiple Linear Regression
- Statistical Interpretation
- Data Visualization
- Econometric Modeling
