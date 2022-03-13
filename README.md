# whale_analysis

This application will analyze investment portfolio, establish baselines for their results, and compare against the broader investment market (S&P 500)

The purpose of the application, and the built in analytical functions, is to rank and determine the best investment oportunities amongst a collection of portfolios vs the broader market. Analytical indicators include:

* Daily Return Percentages
* Cumulative Returns (Long-term Growth)
* Volatility Visualization (Box Plot)
* Standard Deviation of the Daily Returns
* Annualized Standard Deviations
* Rolling 21-day Standard Deviation Visualization (Line Chart)
* Sharpe Ratios
* Portfolio Covariance from Market (for top 2 Portfolios)
* Portfolio Beta rolling 60-day Visualization (Line Chart) (for top 2 Portfolios)

The following images show examples of the analytical outputs from this application.

![Image of a line chart showing cumulative returns for the imported portfolios vs. the S&P 500 market from late 2014 through late 2020](https://github.com/rjohnson617/whale_analysis/blob/main/Resources/cume_return.png?raw=true)

![Image of a box plot showing daily return volatility for the imported portfolios vs. the S&P 500 market from late 2014 through late 2020](https://github.com/rjohnson617/whale_analysis/blob/main/Resources/return_volatility_box.png?raw=true)

![Image of a line chart showing rolling 21-day standard deviations for the imported portfolios vs. the S&P 500 market from late 2014 through late 2020](https://github.com/rjohnson617/whale_analysis/blob/main/Resources/roll21_std_v_market.png?raw=true)

![Image of a bar chart showing Sharpe Ratios for the imported portfolios vs. the S&P 500 market from late 2014 through late 2020](https://github.com/rjohnson617/whale_analysis/blob/main/Resources/sharpe_ratio_bar.png?raw=true)

![Image of a line chart showing a portfolios rolling 60-day Beta vs. the S&P 500 market from late 2014 through late 2020](https://github.com/rjohnson617/whale_analysis/blob/main/Resources/portfolio1_60_day_rolling_beta.png?raw=true)

---

## Technologies

### Python, Pandas, Pathlib, NumPy, JupyterLab, Matplotlib

The application is written in Python through a JupyterLab notebook and utilizes the Pandas, Pathlib, NumPy, and maplotlib libraries to bring in stock portfolio data, scrub and analyze, and then visulaize for the final analysis

---

## Contributors

Code produced by Ryan Johnson

---

## License

[MIT]

Copyright (c) [2022] [Ryan Johnson]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.