# amazon-stock-forecast
“Forecasting Amazon stock prices using Python regression and ARIMA models.”
Tools Used
- Python (pandas, statsmodels, matplotlib)
- Jupyter Notebook
- Regression & ARIMA time series forecasting
Project Overview
This project analyzes Amazon stock data to forecast future prices. 
The model compares linear regression and ARIMA approaches, with error metrics to evaluate accuracy.
Files
- `amazon_forecast.ipynb`: Python notebook with full analysis
- `data/amazon.csv`: Stock dataset (Weekly prices)
- `results.png`: Visualization of forecasted trend
Key Outcomes
- Built ARIMA(0,1,1) model to capture stock trend
- Regression model explained ~80% of variability
- Forecasted prices 73 weeks forward

echo "# amazon-stock-forecast" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/EthanG-Data/amazon-stock-forecast.git
git push -u origin main
