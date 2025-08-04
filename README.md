# S&P 500 Historical Analysis with Benford's Law & Rolling Returns

This project explores historical daily closing prices of the S&P 500 index using two distinct approaches:

1. **Benford's Law Analysis** – to test whether the leading digits of stock prices conform to natural data distributions.
2. **Rolling Return Analysis** – to assess long-term investment outcomes over various 5-year periods.

---

## 📈 Features

- ✅ Fetches and visualizes all available S&P 500 daily closing prices using [Yahoo Finance](https://finance.yahoo.com/).
- ✅ Tests conformity to [Benford’s Law](https://en.wikipedia.org/wiki/Benford%27s_law) using a chi-squared test.
- ✅ Visualizes observed vs. expected digit distributions.
- ✅ Calculates and analyzes 5-year rolling returns based on log returns.
- ✅ Shows how many 5-year periods in history would have resulted in a loss.

---

## 🛠️ Dependencies

Install required packages:

```bash
pip install yfinance pandas numpy matplotlib seaborn scipy python-dateutil
