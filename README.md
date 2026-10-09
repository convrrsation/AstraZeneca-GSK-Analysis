# AstraZeneca-GSK-Analysis
# AstraZeneca vs GSK: Risk and Return Analysis

**Question:** Which of AstraZeneca and GSK gave better returns relative to risk over the past five years?

**Method:** Downloaded daily adjusted prices using yfinance, calculated daily returns in pandas, and computed total return, annualised return, annualised volatility and correlation.

**Results**

| | AstraZeneca | GSK |
|---|---|---|
| Total return | [40.1]% | [31.5]% |
| Annualised return | [7.0]% | [5.6]% |
| Annualised volatility | [24.6]% | [23.0]% |

Correlation: [0.51]

![Growth of 100 invested](chart.png)

**Conclusion:** As a whole, AstraZeneca returned 40.1% in total (7.0% annualised) against 31.5% (5.6%) for GSK over the past five years. AstraZeneca was slightly more volatile (24.6% vs 23.0% annualised), but its return per unit of risk was higher, at about 0.29 compared with 0.24 for GSK. The two stocks had a correlation of 0.51, so they moved together moderately suggesting holding both would give some diversification. This analysis covers only two companies over a single five-year window and past performance doesn't predict future returns. The risk-adjusted figure is a simple return-to-volatility ratio, not a full Sharpe ratio, as it doesn't subtract a risk-free rate. Furthermore, it is important to note that the sharp drop in GSK stock mid-2022 is reflective of the Haleon demerger that took place and not of marketloss, and that the comparison of the two data sets is therefore limited as a result.

**Limitations:** Two companies over one period; past performance does not predict future returns; the return-to-volatility ratio is not a full Sharpe ratio.

**Tools:** Python, pandas, matplotlib, yfinance
