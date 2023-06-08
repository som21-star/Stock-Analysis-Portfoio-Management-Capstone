# Stock-Analysis-Portfoio-Management-Capstone

In the recent past, the industry of wealth management has seen a lot of growth. Every individual or business actively searches for opportunities to get the maximum returns. However, in most of the cases, they either lack the skills to identify the right investment opportunity, or there is a shortage of time for finding these opportunities. Hence, this gave rise to the dedicated individuals who perform this task on behalf of the investors for a commission - Portfolio managers.

A portfolio manager makes investment decisions and carries out other related activities on behalf of vested investors. They work with a team of analysts and researchers, and their main objective is to realise the needs of the investor and suggest a suitable portfolio that meets all the expectations. They are responsible for establishing the best investment strategy, selecting appropriate investments along with the right allocation. However, in doing so, they face a lot of competition in the form of other portfolio managers and rival firms. Therefore, the portfolio manager has to use the available resources to provide the best solution to the investor.

Following points summarise the expected tasks in the assignment:

You must use the elements of technical analysis to understand the trend of the underlying stocks. The metrics associated with risk and returns must help you realise whether the security meets the criteria of your investor’s financial goals. You must use the metrics and the visualisations to compare the performance of the available securities against each other, and also against the market index, S&P500. The findings should be aligned with the investor persona to select the appropriate stocks for the portfolio. You are expected to validate the same using the Capital Asset Pricing Model (CAPM) before including the stock in the portfolio. After the selection of suitable stocks, you must apply a suitable predictive model to estimate the returns from the portfolio at the end of the investment period. You must check if the portfolio has the potential to fulfil the financial goals of the investor.

You are provided with the following information for 12 stocks of leading companies listed in New York Stock Exchange(NYSE): Date Open price: Price of stock at the start of the day Close price: Price of stock at the end of the day High price: Highest price reached by the stock on that day Low price: Lowest price reached by the stock on that day Adjusted close price: Stock price adjusted to include the annual returns (dividends) that the company offers to the shareholders Volume traded: Number of stocks traded on the day The information for every stock ranges from 1st October 2010 to 30th September 2020. The stocks belong to different domains: Technology/IT Travel/Aviation/Hospitality Banking/Financial Services and Insurance Pharmaceuticals/Healthcare/Life Sciences To help you with the market benchmark, you are given the S&P 500 index prices for the same period.

Data Exploration As part of exploration, you must create visualisations and evaluate the performance metrics that help in summarising the stock. The final outcome should reflect all the points mentioned in the video. Moreover, the findings should be backed by your understanding of the concept or the facts from the industry.

Stock Analysis and Portfolio Management - CAPM As part of this task, you must execute your responsibilities as the portfolio manager. You must use the information about the investor to create a profile, and use it along with the obtained results to create a portfolio of stocks that have the potential to meet the financial goals of your investor. You must also use other measures of technical analysis like the Sharpe ratio to validate the same. Hint: Use the CAPM to understand the expected returns and volatility of the stocks against the market.

Stock Price Prediction - Validation A portfolio manager is also expected to validate the results obtained. As part of this task, you leverage the machine learning models to check the future prices of the stocks present in the portfolio. Based on the results, you can back your portfolio in case the investor is able to achieve the desired results. However, in case it doesn't have satisfactory performance, you can try another combination of stocks in the portfolio that will perform well. Note: You can explore additional concepts associated with stocks to derive new features from the available values - price and volume. You can add them to your model to help improve performance.

Data Storytelling and Business Impact (Report + Video presentation) Post the analysis, you must summarise all the findings, insights, visuals and recommendations in the form of an executive report to your investor. Your report must also provide the features of the investors based on the information provided. Moreover, you are also expected to share a video presenting all the information to the investors.

Insights and Findings
--Performance, Volatility, Correlation and Diversification are the strong indicators.

The maximum drop for Google was -11.10% on 1360(datevalue)
The maximum and minimum daily average return of the stocks respectively Google 0.012804 Goldman Sachs -0.000047
The distribution of the Adj Close price is very right-skewed for Google stock and for the entire stocks as well.
The most risky and the least risky stock is Google and Apple respectively with respect to the standard deviation of the daily returns.
--Selection of relevant stocks using CAPM model

Stock Expected Return AAL 2.362632 AMZN 0.029922 BHC 0.678251 DB 0.087519 HA 0.454538
The Beta coefficient is the highest for AAL(American Airlines Group Inc) 0.077699 that suggests it is the most in line stock aligned with the market.
--Model Performance Cross validated fine tuned Random Forest Regressor is the best model with the following result Mean Squared Error: 143.4289030574884 Mean Absolute Error: 3.4828616981822145 R-squared: 0.9996490697285944
