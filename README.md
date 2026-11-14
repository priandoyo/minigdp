# MiniGDP – GDP Growth Prediction

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/priandoyo/minigdp/blob/main/gdpmodel.ipynb)

A small Python-based econometric experiment exploring the relationship between investment growth and GDP growth using **Ordinary Least Squares (OLS) regression**.

## What It Does

1. Generates synthetic investment-growth data for 2010–2019.
2. Creates GDP-growth values using an assumed linear relationship plus random noise.
3. Organizes sample data using Pandas.
4. Estimates an OLS regression using Statsmodels.
5. Predicts GDP growth when investment growth is set to 6%.

## Technologies

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical computation |
| Pandas | Data manipulation |
| Statsmodels | Econometric modeling and regression |

## Model

GDP Growth = α + β (Investment Growth) + ε

## Requirements

- numpy
- pandas
- statsmodels

## Important Note

This project uses synthetic data, not observed national economic statistics. It is intended for learning and demonstrating econometric modeling, OLS regression, statistical analysis, and prediction. It is not an empirically validated GDP forecasting model.

## Run the Notebook

Click the **Open in Google Colab** badge above to execute the notebook directly in Google Colab.

[View Notebook on GitHub](https://github.com/priandoyo/minigdp/blob/main/gdpmodel.ipynb)
