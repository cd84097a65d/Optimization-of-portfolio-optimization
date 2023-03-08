# Optimization of portfolio optimization.

# Goal
The modern portfolio theory can suggest the ratios of assets in the portfolio. The **single parameter** used inside is the time span of time series. 
* That would be great to optimize that parameter to reach maximal profit of the portfolio. 
* Second, to increase the portfolio profit we can use warrants of both types, call and put to be independent from the market direction. The warrant price depends on excercise price. That price has to be optimized. 

## Plans
In this repository I plan to do following:
* Get the prices of several assets since 2000.
	* The prices will be distributed as text file to allow better tracking of changes using GitHub. The distribution of 
	* The possible splits should be taken into account. 
* Use [modern portfolio theory](https://github.com/cd84097a65d/Portfolio-optimization-using-efficient-frontier-curve) for optimization. 
* Since optimization of one set of time series takes too much time, use [OpenCL](https://github.com/Excel-lent/ClooWrapperVBA) to increase performance. 
* Optimize three investment strategies at once (since covariance matrix of two last strategies can be simple constructed from the first one):
	* Simple: just bying of assets is allowed. 
	* Separate optimization of call and put warrants. 
	* Call and put warrants are optimized together. 





