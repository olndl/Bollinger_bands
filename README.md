# Quantitative Methods and Financial Indicators

This repository contains a small portfolio of Jupyter notebooks covering numerical methods, regression modeling, feature encoding, and a financial technical indicator. The notebooks are written as readable reports: each one introduces the problem, implements the method, and includes the main result, validation step, or visualization code.

## Notebooks

| Notebook | Topic | What it demonstrates |
| --- | --- | --- |
| `brent_bollinger_bands.ipynb` | Financial indicators | Bollinger Bands for Brent crude oil futures using a rolling window and standard deviation bands. |
| `linear_regression_sgd.ipynb` | Machine learning from scratch | Linear regression solved with both the normal equation and stochastic gradient descent. |
| `binomial_glm_target_encoding.ipynb` | Statistical modeling | Binomial GLM with K-fold target encoding for categorical predictors and odds-ratio interpretation. |
| `matrix_power_limits.ipynb` | Numerical linear algebra | Iterative matrix-power analysis with threshold-based stopping conditions and tests. |
| `taylor_approximation_error.ipynb` | Numerical analysis | Grid-based error analysis for a Taylor approximation, including a 3D error-surface visualization. |

## Repository Highlights

- Self-contained implementations of core numerical and modeling routines.
- Visualization code for financial time series and approximation-error analysis.
- Lightweight validation examples where appropriate.

## Tech Stack

- Python
- Jupyter Notebook
- NumPy
- pandas
- matplotlib
- statsmodels
- scikit-learn
- yfinance

## Running the Notebooks

Create and activate a Python environment, then install the main dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Some notebooks expect local datasets that are not currently included in this repository:

- `linear_regression_sgd.ipynb` expects `advertising.csv`.
- `binomial_glm_target_encoding.ipynb` expects `smoke.csv`.

The Brent Bollinger Bands notebook downloads market data with `yfinance`, so it requires internet access when re-run.

## Project Structure

```text
.
├── README.md
├── binomial_glm_target_encoding.ipynb
├── brent_bollinger_bands.ipynb
├── linear_regression_sgd.ipynb
├── matrix_power_limits.ipynb
├── requirements.txt
└── taylor_approximation_error.ipynb
```

