# Credit-Union-Member-Financial-Planner
This program evaluates a credit union member's current financial holdings in crypto, stock and bonds using API calls for current prices. It then evaluates the member's current portfolio has enough emergency funds (assumed to be three months worth of income). A Monte Carlo simulation is then run to forecast probable (95% confidence ratio based on past performance) financial futures for different stock and bond portfolio proportions on 30 and 10 year scales and give the member a likely range of outcomes for them to gauge their time to retirement possibility and the difference it makes if they increase their portfolio weight to a higher percent of stock holdings. 

# Technologies

This program is written in Python 3.7 and must be run in Jupyter Lab. The following libraries are used:

- os
- requests
- json
- pandas
- dotenv
- alpaca_trade_api    
    
# Installation Guide

You will need to verify that you have installed the libraries listed in the Technologies section. In addition, you must obtain an ALPACA_API_KEY and an ALPACA_SECRET_KEY. You need to get an Alpaca account to do so, and then once you have these keys place them in a file named `.env` in the program folder with the following syntax:

```ALPACA_API_KEY = "youralpacaapikeyhere"```

```ALPACA_SECRET_KEY = "youralpacasecretkeyhere"```

## Usage

Run the program `financial_planning_tools.ipynb` in Jupyter Lab.

You will see output that looks like this:

![](https://raw.githubusercontent.com/phodsman/Credit-Union-Member-Financial-Planner/main/Screenshot%202021-10-21%20111625.png)

## Contributors
This program was written by Preston Hodsman based on a request for analysis from Trilogy Education Services, a 2U, Inc.

## License
MIT