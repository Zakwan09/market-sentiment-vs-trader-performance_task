# Trader Performance vs Market Sentiment – Summary

## Methodology  

For this analysis, I used two datasets — one for Bitcoin market sentiment (Fear/Greed) and another for historical trader data from Hyperliquid.  

First, I cleaned both datasets and checked for missing values and duplicates. Then I converted the timestamp column into datetime format and aligned both datasets on a daily level using a common date column. After merging the data, I created some important metrics like PnL, win rate, trade size (Size USD), trade frequency, and long/short indicator.  

I also divided traders into different groups such as high vs low risk, frequent vs rare traders, and winners vs losers to understand their behavior better.

---

## Insights  

1. **Performance changes with sentiment**  
   During Greed days, traders generally make higher profits but with more fluctuation. During Fear days, profits are lower but more stable.

2. **Trader behavior changes**  
   Traders take bigger positions and trade more during Greed. During Fear, they reduce trade size and become more careful.

3. **Different types of traders behave differently**  
   Frequent traders are more consistent. High-risk traders perform well in Greed but face bigger losses in Fear. Also, profitable traders manage risk better and adjust their strategy.

---

## Strategy Recommendations  

1. **During Fear markets**  
   It is better to reduce trade size and avoid high-risk trades since the market is uncertain.

2. **During Greed markets**  
   Traders can trade more actively to take advantage of opportunities, but they should control risk and not overtrade.

---

Overall, this analysis shows that market sentiment affects both trader behavior and performance, and adjusting strategies based on sentiment can help improve results.
