# Momentum-Index
Building a Momentum Index of NSE NIFTY index stocks using MSCI methodology

# Description:
This project replicates the MSCI Momentum Index for the Indian stock market using the NIFTY 500 index. It involves data processing, ranking stocks based on momentum factors, and constructing a momentum-based portfolio.

# Methodology used:
Data extraction and preprocessing from Bhavcopy.
Calculation of momentum scores based on MSCI Methodology: 
- Step 1: Selecting appropriate universe of securities (NIFTY 500)
- Step 2: Calculating Momentum Score
- Step 3: Selecting stocks for Index development
- Step 4: Assign weights
Performance evaluation of the momentum index.

# Technologies Used:
Python
Libraries: Pandas & NumPy
Packages: Bhavcopy

# Results:
Achieved **32.8% returns**, outperforming NIFTY 500’s 15.6% returns in the same timeframe, with automated index calculations and systematic rebalancing in Python 

# Possible Future Enhancements:
Backtesting & Benchmarking: Compare the momentum index's performance against NIFTY 500, analyzing returns, volatility, and drawdowns.
Automated Data Updates: Implement scripts to fetch and update Bhavcopy data periodically for real-time analysis.
