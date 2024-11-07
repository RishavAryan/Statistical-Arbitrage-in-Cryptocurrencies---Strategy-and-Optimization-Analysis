# Statistical-Arbitrage-in-Cryptocurrencies---Strategy-and-Optimization-Analysis
Explores statistical arbitrage strategies in the cryptocurrency market 
## Overview
This project explores statistical arbitrage strategies in the cryptocurrency market by using momentum, reversal, and combined strategies on 10 major cryptocurrencies. Key metrics like Sharpe Ratio, Max Drawdown, and Volatility were used to evaluate the performance of these strategies and identify optimized trading parameters.

## Cryptocurrencies Analyzed
- Bitcoin (BTC-USD)
- Ethereum (ETH-USD)
- Binance Coin (BNB-USD)
- Cardano (ADA-USD)
- XRP (XRP-USD)
- Solana (SOL-USD)
- Polkadot (DOT-USD)
- Dogecoin (DOGE-USD)
- Litecoin (LTC-USD)
- Avalanche (AVAX-USD)

## Methodology
- Momentum Strategy: Uses moving averages to signal buy (bullish) and sell (bearish) trends based on the relationship between short-term and long-term moving averages.
- Reversal Strategy: Relies on the Relative Strength Index (RSI) to determine overbought and oversold conditions, triggering buy signals below 30 and sell signals above 70.
- Combined Strategy: Combines momentum and reversal strategies with volatility filters to avoid low-confidence transactions.

## Performance Metrics
- Sharpe Ratio: Assesses risk-adjusted returns.
- Max Drawdown: Indicates the maximum loss from peak to trough.
- Volatility: Standard deviation of returns as a measure of risk.
- Alpha and Beta: Measures performance relative to a benchmark.

## Key Findings
- Momentum vs. Reversal: Momentum strategies generally outperformed reversal strategies, especially in volatile assets like SOL-USD and BNB-USD.
- Combined Strategy Performance: The combined strategy underperformed, showing negative Sharpe ratios and high drawdowns in most cases, with SOL-USD being a rare exception.
- Optimization Results: Optimizing parameters (e.g., RSI thresholds, MA periods) improved performance for certain assets, but significant risks remained, as indicated by high drawdowns.
- Volatility vs. Sharpe Ratio: Scatter plots revealed that some assets, like AVAX-USD and DOGE-USD, exhibited high volatility with poor risk-adjusted returns, while SOL-USD showed a balanced risk-reward profile.

## Recommendations
- Focus on Momentum Strategies: Momentum approaches showed better overall results, particularly in trending assets like SOL-USD and BNB-USD.
- Use Combined Strategy Cautiously: Combined strategies did not balance risks effectively, so they should be used with caution.
- Parameter Optimization: Regularly optimize strategy parameters for assets with high Sharpe ratios post-optimization, such as SOL-USD and BNB-USD.
- Risk Management: Manage high volatility by incorporating volatility-adjusted risk limits for assets with sharp drawdowns.

