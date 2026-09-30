# Coin-Flip-simulator
Simulator that runs thousands of coin flips, calculates expected value, and visualises the distribution of outcomes.
* Vectorized Simulation Engine: Built a high-performance simulation using NumPy vectorization to model 10,000 independent trials, each containing 1,000 coin flips ($10^7$$10^7$ data points total) in milliseconds, bypassing slow python loops.
* Quantitative Analytics & Validation: Analysed and confirmed the Law of Large Numbers by tracking the convergence of the empirical mean to the theoretical Expected Value ($E[X] = 0$$E[X] = 0$).
* Statistical Distributions: Verified the Central Limit Theorem (CLT) by fitting a Gaussian (Normal) curve over the empirical payouts, visualizing a near-perfect distribution ($\mu \approx -0.05, \sigma \approx 31.33$).
