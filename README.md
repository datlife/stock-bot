# stock-bot
Implementation of Rule #1 Investing by analyzing stock historical data and making prediction on historical data to test if his advice, or hypothesis, is actually valid.

## Goals:
* Analyze historical stock data based on his indicators as a feature vector ==> list of potentially good stocks.
* Given a list of "good" stocks, validate the outcome on historical data as well ==> determine if his feature vector is good.

## Action Plan:
* Collect all US publicly traded stock data
* Construct a model based on his 5 indicators
* Run the model against historical data and analyze the result


## Summary:
* Invest in company that you know their business or has a competitive advangages (Pfizer, Walmart, Windows, PG&E) -> monoply score
* Five indicators more than 10 years:
  * Return On Investment Capital (ROIC): at least 10% every year
  * Growth On Company Equity (Asset - Debt): 10% every year
  * Earning Per Share (EPS)
  * Sale Growth Rate
  * Free Cashflow Growth Rate (Operational Cash - Capital Expenditure)
* Effectiveness of CEO (owner-mindset)
* Big Margin of Safety: Ideal buy = (Value - Price) < 50%
