# Lookback Option Valuation

A lookback option gives the option holder the right but not the obligation to buy the underlying asset at the lowest price. It pays a single call-option-style payoff based on the performance of the underlying asset’s final price relative to its initial price, where both the initial and final prices are computed using a lookback formula.

The initial price is taken as the highest price observed over a set of Initial Lookback Dates. The final price is taken as the maximum of the running cumulative average, observed over a set of Payoff Observation Dates.

Lookback options are designed to provide investors with the opportunity for an enhanced return while reducing the downside risks with partial protection that “buffers” any negative performance of the Reference Index over the term of the Notes. The “look-back” feature offers holders an optimal entry point for their investment.

Lookback options provide a return that is determined by the optimal performance of a single asset or basket on a set schedule of lookback dates. The lookback options could have fixed and
floating strikes.

	Payoff
Call option for floating strike:
	The payoff is c_T=max⁡( S_T-S_(0,T)^min,0)
where   ~ lowest price during the option’s lifetime

Put option for floating strike:
The payoff is p_T=max⁡( S_(0,T)^max-S_T,0)
where   ~ highest price during the option’s lifetime
Call option on fixed strike:
The payoff is payoff:  	
where X ~ strike

Put option on fixed strike:
The payoff is  
where X is the strike

	Lookback option on fixed strike
	Lookback option on floating strike
	Asian lookback option
	Callable lookback note


References:

https://finpricing.com/lib/EqLookback.html

https://fliphtml5.com/download/download-pdf-file.php?str=x0DZh9GTud3bENXamIzNyQDO3MTPkl0av9mY


