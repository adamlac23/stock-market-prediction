# Stock Market Direction Prediction with XGBoost

This project uses macroeconomic indicators and market data to predict the direction of stock market movements, implementing various machine learning models including XGBoost.

## Project Structure

- `stock_pred.ipynb` – Jupyter Notebook containing data preprocessing, model training, evaluation, and backtesting strategy
- `requirements.txt` – List of required Python packages
- `.gitignore` – Files and folders ignored by Git

## Key Features

- Use of macroeconomic indicators like CPI, Unemployment, and Fed Funds Rate
- Logistic Regression and XGBoost classification models
- Backtesting investment strategy based on predicted directions
- Sharpe Ratio, annualized return, and volatility evaluation

## How to Run

1. Clone the repository
2. Create a virtual environment
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook stock_pred.ipynb
```

## License

MIT License
