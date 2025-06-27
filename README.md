# Mercedesbenz_DataAnalytics
This project performs end-to-end data analysis, visualization, and time-series forecasting on Mercedes-Benz Group AG (MBG.DE) historical stock data 




🧾 Overview:
This project presents a high-resolution exploratory data analysis (EDA) and feature-enriched financial time series study on the historical stock performance of Mercedes-Benz Group AG.

With a heavy emphasis on statistical signal processing, market behavior interpretation, and technical indicator profiling, the project serves as a comprehensive template for financial data analysts, quant researchers, and applied statisticians.

📌 Core Objectives:
Extract temporal, cyclical, and structural patterns in MBG.DE stock movements.

Visualize volatility regimes, price momentum, volume bursts, and trend reversals.

Decompose the stock's price into trend, seasonality, and residual noise using robust statistical models.

Study time-based dependencies (monthly, weekly, weekday-wise) through heatmaps and pivot tables.

Profile trading activity through high-resolution visualizations: candlesticks, rolling variance plots, moving averages, and volume surges.

Evaluate technical indicators like Bollinger Bands, MACD, RSI, and ATR for quantitative diagnostics.

🧠 Key Highlights
Feature Category	Techniques / Visuals Covered
Time Series Analysis	Line plots, STL decomposition, Rolling stats, Volatility bands
Technical Indicators	Bollinger Bands, RSI, MACD, ATR, CCI, EMA, Momentum Oscillator
Seasonality Patterns	Yearly/Monthly boxplots, pivot tables, weekday cycle plots
Volume & Liquidity	Volume spikes, VWAP, intraday volume correlation
Statistical Profiles	Distributional diagnostics, outlier profiling, correlation heatmaps
Candlestick Analysis	High-frequency OHLC visualization using Plotly and Matplotlib
Anomaly Detection	Price shocks, volatility explosions, Z-score detection on residuals
Sector-Specific Metrics	Adjusted close insights, hedging zone detection, spread trend quantification



📂 Dataset Information
Source: Historical Market Data (CSV)

Ticker: MBG.DE (Mercedes-Benz Group AG)

🧮 Analytical Layers
1. 📅 Temporal Dynamics
Long-term price movement analysis (raw & adjusted prices)

De-trending and moving average smoothing

Volatility clustering and market shock intervals

2. 📊 Descriptive Statistics
High–Low spread diagnostics

Price returns: log returns, daily percentage change

Kurtosis and skewness of price series

Tail-risk (VaR visualizations)

3. 📈 Advanced Visual Analytics
120+ Custom visualizations including:

Plotly Candlesticks & Volume Overlays

OHLC + VWAP hybrid

RSI/Bollinger Band/ATR time-series overlays

Dynamic correlation heatmaps by market phase

4. 🧭 Seasonality & Frequency Decomposition
STL & Classical Decomposition

Residual analysis

Stationarity diagnostics using ADF/KPSS tests

5. 🧩 Feature Enrichment
Rolling mean/STD windows (10, 20, 50, 100)

Cross-timeframe volatility analysis

Daily, weekly, monthly aggregation and pivot comparison

Time-based behavior clustering

🔍 Sample Visual Outputs
📈 Stock Price Over Time with 20/50-day moving averages

📊 Volume Spikes with Return Overlays

🔥 Rolling Volatility (30d) for regime detection

📆 Seasonality Heatmaps (month × year)

📌 Candlestick & Bollinger Band Convergence Zones

🧭 RSI + MACD Confluence Regions

🧪 Statistical Diagnostics
✅ Stationarity Tests: Augmented Dickey-Fuller, KPSS

✅ Z-score Thresholding: For return anomalies

✅ Outlier Detection: Price deviation vs rolling benchmark

✅ Auto-Correlation Functions (ACF, PACF)

✅ Correlation Breakdown: Heatmap of lag relationships



🖥️ Usage Instructions
Clone this repository or copy the files to your project.
Place the dataset in the path Mercedes/MBG.DE[1].csv
Launch EDA_and_Timeseries_Analysis.ipynb in Jupyter Notebook.
Run all cells to generate the complete analysis report and visuals.


💼 Real-World Applications
📊 Equity Research: Historical stock behavior profiling

📈 Risk Management: Detect volatility regimes

📉 Quant Strategy Development: Signal detection from Bollinger, RSI, MACD

🧮 Market Microstructure: Understand volume dynamics

🧪 Financial Engineering: Pre-modeling diagnostics for statistical and DL-based predictions


🔮 Future Enhancements
🧠 Integrate anomaly detection using Isolation Forest
📚 Compare against peer group: BMW, Audi, Porsche
⏳ Integrate forecasting models in a separate notebook (Prophet, ARIMA, LSTM)

🧑‍💻 Author
Sourish

📜 License
This project is open-source under the MIT License.
Use for research, educational, or portfolio purposes.

