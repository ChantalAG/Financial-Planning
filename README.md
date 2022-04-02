# Financial-Planning
Financial Planning - API Assignment

<img src="https://github.com/ChantalAG/Financial-Planning/blob/main/Financial-Planning.jpg" width="400" height="200">

## Background

The financial analysis tools in this project will use APIs to help users enhance financial health, assess monthly personal finances, and be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.

The first tool will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money  as an emergency fund.

The second will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds. Monte Carlo simulations will be run to project the portfolio performance at 30 years and then at 5 and 10 years for early retirement projections with a larger initial investment. 

The following assumptions were used:
* The average household income for each user is $12,000.
* Every user has a savings portfolio composed of cryptocurrencies, stocks and bonds.
* Amount of crypto assets: 1.2 BTC and 5.3 ETH.
* Amount of shares in stocks and bonds: 50 SPY (stocks) and 200 AGG (bonds).


## Resources
Files:
* [MC ForecastTools Toolkit](https://github.com/ChantalAG/Financial-Planning/blob/main/MCForecastTools.py)

This project will utilize two APIs:
* The Alpaca Markets API will be used to pull historical stocks and bonds information.
* The Alternative Free Crypto API will be used to retrieve Bitcoin and Ethereum prices.

The documentation for these APIs can be found via the following links:
* [Free Crypto API Documentation](https://alternative.me/crypto/api/)
* [AlpacDOCS](https://alpaca.markets/docs/)

## Technologies Used 
* Jupyter Notebook
* Pandas 1.3.5
* API 

## Examples
Visualization of savings:

<img src = "https://github.com/ChantalAG/Financial-Planning/blob/main/Images/Composition%20of%20Personal%20Savings.png">

Montecarlo simulation results and the probability distribution/confidence intervals for 30 years, 5 years and 10 years for retirement portfolio. 

<img src = "https://github.com/ChantalAG/Financial-Planning/blob/main/Images/MC_thirtyyear_sim_plot.png">
<img src = "https://github.com/ChantalAG/Financial-Planning/blob/main/Images/thirtyyear_dist_plot.png">

## Contributors
Chantal Garnett 
