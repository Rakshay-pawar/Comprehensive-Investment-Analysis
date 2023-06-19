# Comprehensive-Investment-Analysis

In my journey through the captivating realm of market dynamics, I embarked on an exploration of daily market data from some of the most prominent players in the business: Microsoft, Intel, Southwest Airlines, McDonald's, and Johnson & Johnson. This data, spanning from the end of 1989 all the way through August 2022, was obtained from the vast reservoir of Yahoo Finance, complemented by the indispensable Kenneth French's Data Library for the daily risk-free rate time series.

My initial endeavor was to transfigure the raw price data into weekly simple total returns, taking care to account for dividends via the Adjusted Close. The fruits of this labor were fascinating: a comprehensive dataset of weekly and annualized mean and standard deviation for each stock. To paint a clearer picture of the relationships between these entities, I went on to compute a correlation matrix.

Continuing my expedition, I constructed the mean-variance frontier for the Intel-Microsoft duo, revealing the minimum-variance portfolio and the efficient frontier. These offered insights into the combination of returns and risks that could be of potential interest to any discerning investor.

But the market is a vast ecosystem. Not content with just a two-stock analysis, I introduced the remaining stocks into the fray. The newly computed mean-variance frontier was plotted against the previous one, adding another layer of depth to the analysis. As I traced the contours of the new minimum-variance portfolio and the efficient frontier, I couldn't help but compare these novel findings with the earlier Intel-Microsoft landscape.

Taking the analysis even further, I incorporated the riskless asset into the picture. With this addition, I was able to construct the tangent portfolio for both the Intel-Microsoft case and the full set of stocks. The comparison of Sharpe ratios between these two scenarios was nothing short of enlightening.

Assuming a risk aversion coefficient of 3.5, I pondered the optimal mix of assets that would include the risk-free asset.

Switching gears a bit, I went ahead and regressed excess stock returns on excess market returns, effectively estimating the betas for the five stocks. It was crucial to compute the standard errors of these estimates to ascertain their reliability.

An essential component of this analysis involved estimating the alphas and their respective standard deviations. This allowed me to explore the idiosyncratic risks of these stocks, an indispensable part of the investment decision-making process.

Lastly, I calculated the sample average excess return and held it against the return predicted by the well-established Capital Asset Pricing Model (CAPM). As I compared these numbers, I sought to understand how accurately the CAPM could predict the level returns, and the relative performance. The results provided valuable insights into the predictive power, and potential shortcomings, of the CAPM in the real-world market dynamics.

Through these rigorous examinations, I have gained invaluable insights into the nuances of these stocks, their performance, and their relationship with market trends, all of which lay the groundwork for informed investment decisions.
