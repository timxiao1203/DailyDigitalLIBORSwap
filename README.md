# Daily Digital LIBOR Swap

A daily digital LIBOR swap is an interest rate swap whose reference interest rate is three-month USD Libor BBA. For each accrual period in the swap, one party receives the reference rate, and pays the reference rate plus a positive spread, but weighted by the ratio of the number of calendar days in the period that the reference rate sets below an upper level to the total number of calendar days in the period.

The payoff amount can be viewed as the value of the sum of a series of daily Libor digital payoffs.  Here we assume that Libor rates are log-normally distributed, and derives an analytical formula for the daily digital payoff.

Consider a particular day in the accrual period above, and let   denote the time (expressed in years) corresponding to this day.  Furthermore let   denote the reference Libor rate at time.  

In order to evaluate Formula (1) we require the joint distribution of A and B  under the  -forward probability measure.  where C denotes the price at time   of a zero-coupon bond with maturity  .   

We note that (3) provides an approximate expression for  , under the  -forward measure, whose accuracy depends on the volatility,  , and Libor setting time,  .

We consider the distribution of the bonds,  and  , in Formula (3.2.2.1). Here we assume that

We note that the choice of distribution for the ratio,  , can be made more rigorous.  In particular if we specify the process for the forward  -period Libor rate, which sets at time  , then this induces the distribution of D.

For example, if the forward  -period Libor rate follows geometric Brownian motion with no drift and with constant volatility, then this induces a shifted log-normal distribution for E.

References:

https://finpricing.com/lib/EqConvertible.html

https://osf.io/wn2ys/wiki/home/

https://osf.io/qzmer/download
