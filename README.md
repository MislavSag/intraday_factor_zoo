TODO:

1. Data Collection

[] Collect 15-min intraday data for 272 factor portfolios (from Aleti 2023 data or construct from raw). There should be 169,965 intraday return observa tions on
each of the factors.
[] Reproduce factor returns for 3 arbitrary factors and for arbitrary years. Choose factors we have data for.
[] Align timestamps and merge factor data with Fama-French market portfolio & ETF (SPY).

2. Summary Statistics

[] Reproduce table 1 from the paper which shows summary statistics of portfolio statistics.
[] Reproduce figure 1 that shows overnight and intraday returns through day.
[] Reproduce figure 2. The plot doesn't have to be the same. But values should make sense.

3. Data preparation

[] Separate continuous and jump components of returns explained in appendinx 1
[] Calculate lagged 15-min, hourly, and daily returns for each factor (HAR-style). Create data for 3 specifcations in the paper:
- [] All, All - 15-minute market return rmkt t,i+1 as the regressand and all the lagged factor returns Xt,i≡∪j∈factorsXt,i,j as the regressors
- [] All, All + Jump 
- [] Cts, All + Jump 

