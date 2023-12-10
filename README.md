# Thesis on Strategy
## Graphs needed
- Summary statistics on all the indices i'm looking at
  - Shenwan 1st level indices
  - 申万一级行业composite
  - SH Composite
  - SS300
  - 中证全指
  - S&P500?
- correlation between all the indices
- time series momentum in t-statistics
- cross-sectional momentum in t-statistics
- correlation between noise level and returns
- cumulative excess return of time series momentum and diversified passive long strategy
- compare different holding sizes
## Sections
### literature review
#### Introduction to a typical sector rotation stratetgy
- Merrill Clock provides the theoretical backdrop of this strategy
- it means you only have to think about the cyclical nature of sectors, not macro or micro factors
- We know that rotation exists. sometimes rotation fast sometimes slow. but in the end it doesnt really matter. 
- All we want is to find the next rotation and achieve superior return. which is why we use momentum.
- empirical findings in the US show that alphas tend to persist for US industry portfolios for some time
  - so now we are going to put forth two statements: 1. whether alphas for industry portfolios persist in cn stock market
  - i feel like we just go with the strategy and not worry about persistence
  - *in that other paper the alpha was regressed on a 36 month rolling window* so we shall do that here too
#### Introduction of Momentum
- xsmom
- talk about paper "does industries exlain momentum?"
  - a great paper that basically answers all of my questions. 
  - It says most momentum strategies simply disappear after controlling for industry momentum. 
  - By contrast, industry momentum investment strategies appear highly profitable even after controlling for other factors
#### introduce concept of noise in time series analysis, different types
- hurst ratio
  - A brief introduction but not much to talk
- tnr
  - There are two papers talking about this
  - cuz the paper shows that with momentum the same less noise means more returns (nusret)
  - Over a six-month holding period, momentum decreases monotonically from 8.86% for stocks with continuous information during their formation period to 2.91% for stocks with discrete information but similar cumulative formation-period returns. (Da, Gurun)
  - it means "frog in the pan" so there is a reason why we want a better measure of noise
- volatility
### Methodology
#### methodology on procuring and processing data
- describing how data is made, what is the shenwan indices and how it's calculated
  - data
  - methodology
### Analysis and Discussion
#### perform regression analysis of trendline factor on data
- regress returns on t-n return (xs or ts doesn't matter. maybe xs is better since we just choose one)
- regress returns on the 3 factor model
#### perform regression analysis of noise on data 
- regress returns on noise (the result should be larger tnr corresponds to lower noise)
- a
- tnr is proposed. it's a more intuitive approach to noise. 
#### strategy description
#### strategy backtest
#### strategy comparison with simple XSMOM and TSMOM with no noise reduction
- 
$m^{\prime}=\frac{\sum x_{i}y_{i}+x_{i}c^{\prime}}{\sum(x_{i})^{2}}$
#### regression analysis for 3 factor alpha
#### analyze what kind of exposure our strategy has to different factors as well as to different economic periods
- if in fact it corresponds to what economic period we want
  - then it means our prediction is quite good, so it has a good underlying economic rationale
  - ![Alt text](image.png)
- other possible sources of return
  - several behavioral biases like cognitive error, conservatism bias, and representative bias, loss aversion bias, overconfidence and self-attribution
  - or overreaction bias, like jagadeesh and titman talked about in their papers
### Conclusion and Revision