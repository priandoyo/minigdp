# MiniGDP — Python for Economic Modelling

**MiniGDP** is a collection of Python notebooks for exploring economic relationships, econometric methods, and macroeconomic modelling.

The repository brings together practical experiments using statistical analysis, econometrics, and machine learning to study economic indicators, understand macroeconomic relationships, and develop predictive models.

It is designed as a hands-on learning and experimentation space for anyone interested in economics, data science, and Python.

## Notebooks

| Notebook | Description | Method |
|---|---|---|
| [GDP Growth Model](gdpmodel.ipynb) | Explore the relationship between investment growth and GDP growth | Ordinary Least Squares (OLS) |
| [Indonesia Inflation Forecast](macrosim.ipynb) | Forecast Indonesian inflation using money supply growth | Random Forest Regression |

### 1. GDP Growth Model — Econometric Regression

An econometric experiment exploring the relationship between investment growth and GDP growth.

**What it does:**
- Generates synthetic economic data for 2010–2019.
- Creates GDP growth observations based on an assumed relationship with investment growth.
- Estimates the relationship using Ordinary Least Squares (OLS).
- Produces a GDP growth prediction based on a specified investment growth rate.

**Model:**

`GDP Growth = α + β × Investment Growth + ε`

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/priandoyo/minigdp/blob/main/gdpmodel.ipynb)

[View Notebook on GitHub](gdpmodel.ipynb)

### 2. Indonesia Inflation Forecast — Machine Learning

A macroeconomic forecasting experiment using World Bank economic indicators and machine learning.

**What it does:**
- Retrieves Indonesia's historical economic data from the World Bank.
- Uses Consumer Price Index (CPI) inflation and broad money (M2) growth.
- Uses current M2 growth to estimate next-year inflation.
- Applies Random Forest regression.
- Evaluates model performance using time-series cross-validation and Mean Absolute Error (MAE).
- Visualizes actual versus predicted inflation.

**Model:** Random Forest Regression

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/priandoyo/minigdp/blob/main/macrosim.ipynb)

[View Notebook on GitHub](macrosim.ipynb)

## Getting Started

You can run the notebooks directly in Google Colab without installing Python locally.

Click the **Open in Google Colab** badge for the notebook you want to explore. Colab opens the notebook in your own session, where you can execute, modify, and experiment with the code. Save a copy to your Google Drive to retain your changes.

Alternatively, clone the repository and run the notebooks using Jupyter:

```bash
git clone https://github.com/priandoyo/minigdp.git
cd minigdp
```

Install the required Python libraries:

```bash
pip install numpy pandas statsmodels pandas-datareader scikit-learn matplotlib
```

## Technologies

| Technology | Application |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Interactive development environment |
| Google Colab | Cloud-based notebook execution |
| NumPy | Numerical computation |
| Pandas | Data manipulation and analysis |
| Statsmodels | Econometric modelling and statistical inference |
| Scikit-learn | Machine learning and model evaluation |
| pandas-datareader | Economic data retrieval |
| Matplotlib | Data visualization |

## Areas of Exploration

MiniGDP is intended to grow into a collection of practical experiments covering:

- Econometric modelling and regression
- Macroeconomic indicators and analysis
- Economic forecasting and simulation
- Time-series analysis
- Machine learning applications in economics

## Disclaimer

MiniGDP is an educational and experimental project. Its notebooks demonstrate modelling techniques and analytical workflows, not official economic forecasts or policy advice.

The GDP growth experiment uses synthetic data rather than observed national statistics. The inflation forecasting experiment uses a deliberately simple model specification and a limited set of economic variables. Its results should not be interpreted as evidence of causality or guaranteed forecasting accuracy.

## Repository

**GitHub:** https://github.com/priandoyo/minigdp

More economic modelling experiments and Python notebooks may be added over time.
