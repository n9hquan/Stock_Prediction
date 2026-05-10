# Vietnam Stock Market Analysis & Portfolio Management

A deep learning project for Vietnam stock market analysis, covering price prediction, trading signal identification, and portfolio construction using historical OHLCV data.

## Project Structure
```
├── notebooks/
│   ├── Task_1.1.ipynb   # Single-feature stock price prediction
│   ├── Task_1.2.ipynb   # Multi-feature stock price prediction
│   ├── Task_1.3.ipynb   # Next-day price prediction with cross-validation
│   ├── Task_2.1.ipynb   # Vietnam multi-feature price prediction
│   ├── Task_2.2.ipynb   # k-th day ahead forecast
│   ├── Task_2.3.ipynb   # k consecutive days forecast
│   ├── Task_3.ipynb     # Buy/Sell trading signal identification
│   └── Task_4.ipynb     # Portfolio construction & risk management
├── data/
│   ├── nasdaq/
│   └── vn/
└── README.md
```

## Data
**NASDAQ** (used in Task 1): standard OHLCV CSV files.
**Vietnam** (used in Task 2, 3, 4): CSV files follow this naming convention:
```
{COMPANY}-{EXCHANGE}-History.csv     # e.g. VNM-VNINDEX-History.csv
{COMPANY}-{EXCHANGE}-Dividend.csv    # e.g. VNM-VNINDEX-Dividend.csv
{COMPANY}-{EXCHANGE}-Industry.csv    # e.g. VNM-VNINDEX-Industry.csv
```

## Running on Google Colab
 
1. Open any notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the required CSV files:
- For Task 1: Use data from nasdaq data
- For Task 2, 3: Use historical data from vn stock historical data
- For Task 4: Use vn dividend history, industry-analysis, and stock historical data of the same company
3. Run all cells in order (`Runtime → Run all`)
