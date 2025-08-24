# How To Analyze Asset Volumes With Python

This repository contains a Jupyter notebook that demonstrates how to analyze the volumes and prices of various financial assets (stocks) using Python, pandas, matplotlib, and plotly.

## Contents

- **How_To_Analyze_Asset_Volumes_With_Python.ipynb**: Main notebook with all analysis, visualization, and export steps.
- **talib_How_To_Analyze_Asset_Volumes_With_Python.ipynb**: Additional notebook demonstrating the use of TA-Lib to calculate and visualize volume-based indicators (AD, ADOSC, OBV) for selected stocks, including practical examples and entry signals.
- **stock_data.csv**: CSV file with historical price and volume data for selected stocks.

## Main Features
- Download historical data from Yahoo Finance (yfinance) or TradingView (tvDatafeed)
- Manage MultiIndex DataFrames with tickers and OHLCV columns
- Analyze volumes by price intervals (Volume Profile)
- Visualize with matplotlib and plotly (interactive and static charts)
- Overlay volume profile and price trend
- Automatic export of charts in JPG format via Kaleido
- Advanced analysis with Kernel Density Estimator (KDE) and Market Profile

## Requirements
- Python >= 3.8
- pandas
- numpy
- matplotlib
- plotly
- kaleido (for image export)
- scipy
- marketprofile
- yfinance (optional)

## Installation
Create a virtual environment and install the required packages:

```bash
conda create -n env_test python=3.10
conda activate env_test
pip install pandas numpy matplotlib plotly kaleido scipy marketprofile yfinance
```

**Note:** Kaleido v1+ requires Google Chrome installed on your system to export images. Download Chrome from https://www.google.com/chrome/ or use the command `plotly_get_chrome`.

## Usage
1. Open the notebook `How_To_Analyze_Asset_Volumes_With_Python.ipynb` in VS Code or JupyterLab.
2. Follow the cells to download data, analyze, and visualize volumes and prices.
3. Charts are automatically exported as JPG files in the working directory.

## Author
- [scimmione1](https://github.com/scimmione1)

## License
MIT License
