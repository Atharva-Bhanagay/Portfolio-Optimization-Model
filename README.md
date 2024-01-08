# Stock Portfolio Optimization and Momentum Trading Project

Objective
The goal of this project is to create a diversified portfolio of stocks by utilizing Modern Portfolio Theory (MPT) and implementing a Momentum Trading strategy. The objective is to strike a balance between risk and profit while comparing different investment approaches.

Sectors:
1. Consumer Discretionary Sector
2. Industrial Sector
3. Technology Sector

Procedures

1. Data Preparation
Thirty stocks were selected, with ten from each assigned sector.
Real-world data was retrieved from the web using Python.
Data cleaning was performed to handle missing values.

2. Momentum Trading for Stock Selection
The Momentum Trading strategy was applied to each stock using data from 2021.
The 8-21 Momentum Trading Strategy was employed to identify the three best-performing stocks in each sector.
Performance of the strategy was visualized with one plot per sector.

3. Top performing Stocks for every Sector:
    1. Consumer Discretionary Sector: TSLA (Tesla) , Low (LOWE's Companies) and AMZN (Amazon)
    2. Industrial Sector: DE (Deere & Company) , CAT (Caterpillar Inc.) and UPS (United Parcel Services Inc.)
    3. Technology Sector: NVDA (Nvidia Corp.) , AAPL (Apple Inc.) and AMD (Advanced Micro Devices Inc.)


4. Modern Portfolio Theory
An optimization model was created to determine optimal portfolio allocations using MPT.
The stocks identified through the 8-21 Momentum Trading Strategy were used for the portfolio.
Data from 2017-2021 was utilized to train the model.
Plots were generated to showcase the expected return for different risk levels.
A portfolio allocation consisting of exactly three stocks was selected from the MPT model's solutions.

5. Analysis
The quality of various investments was evaluated using data from 2022.
Comparison included:
Buy-and-hold strategy for the MPT portfolio
8-21 Momentum trading on S&P 500 index (^GSPC)
Buy-and-hold strategy for the S&P 500 index (^GSPC)

