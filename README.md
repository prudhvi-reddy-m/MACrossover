## 📊 Moving Average Crossover Backtesting

### 🎯 Hypothesis
The purpose of this backtesting was to evaluate the effectiveness of a moving average crossover strategy using historical market data. The strategy involved utilizing a short-term moving average (MA 30) and a long-term moving average (MA 100) to generate buy and sell signals.

### Process

1. **Data Collection:**
   - The backtesting began with gathering raw historical market data, including Open, High, Low, Close prices, and Volume. This data was adjusted for factors such as splits and dividends to ensure accuracy.

2. **Data Preparation:**
   - Adjusted prices and volumes were calculated to reflect the true value of the asset. This prepared data was used for the backtesting process.

3. **Signal Generation:**
   - 📈 **Buy Signal**: The strategy hypothesized that a buy signal occurs when the short-term moving average (MA 30) crosses above the long-term moving average (MA 100). Conversely, a sell signal is generated when the short-term MA crosses below the long-term MA.
   - 📉 **Sell Signal**: These moving averages were computed based on the adjusted close prices.

4. **Trade Execution:**
   - Trades were executed based on the generated signals. A buy order was placed when a buy signal was triggered, and a sell order was placed when a sell signal occurred. The trading prices and resulting profit/loss for each trade were recorded.

5. **Performance Evaluation:**
   - The strategy's performance was summarized by evaluating key metrics such as total returns, the number of positive trades (profitable trades), and the number of negative trades (loss-making trades).

### 📈 Output

- **Total Returns:** The backtesting resulted in a cumulative return of -0.401864 (or approximately -40.19%) over the testing period.
- **Number of Trades:** A total of 30 trades were executed during the backtest.
  - **Positive Trades:** 9 trades ended with a profit. 🟢
  - **Negative Trades:** 21 trades resulted in a loss. 🔴

### Conclusion
The backtesting showed that the moving average crossover strategy yielded a negative return of -40.19%, with a greater number of losing trades than winning ones. This suggests that the strategy, in its current form, may not be effective and could require significant refinement or a different market context to be profitable.

