# OU-Pairs-Trading-using-OKLO-and-NNE
Modeling the mean-reverting price relationship of NNE &amp; OKLO (nuclear sector) using a Langevin-style Ornstein-Uhlenbeck process. Includes MLE calibration, Monte Carlo risk simulations, and a LaTeX research paper for SSRN.
Mathematical Progress
- [x] Logarithmic Spread Transformation
- [x] Stationary Pair Identification (NNE/OKLO)
- [X] Ornstein-Uhlenbeck Parameter Calibration (MLE)
- [X] Monte Carlo Path Simulation

Research Log
Day 1: Environment setup using Anaconda Navigator and GitHub Desktop. Started repository and linked local "Lab" to the cloud.
Day 2: Data Acquisition pipeline. Resolved `KeyError: 'Adj Close'` by refactoring the `yfinance` multi index pull for NNE and OKLO.
Day 3: Exploratory Data Analysis. Identified mean-reverting characteristics in the NNE-OKLO log-spread. Verified residual distribution (excess kurtosis).
Day 4: Parameter Calibration. Derived Ornstein-Uhlenbeck parameters using Linear Regression. Watched a few videos on YouTube about Monte Carlo for quant finance.
Day 5: Stochastic Simulation. Implemented Monte Carlo paths. Resolved `IndentationError` in the nested simulation loops. Visualized 100 potential "alternate realities" for the spread.
