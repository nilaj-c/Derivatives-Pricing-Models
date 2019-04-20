# Derivatives-Pricing-Models

Repository of codes to calculate option prices using various models

1. <strong> binomial-pricing-eu-am</strong>: code to calculate the price of an European or American Put or Call option using the Cox-Ross-Rubinstein model. The code has a separate function to calculate the stock price lattice which would be reused later.

2. <strong> bsm-model </strong> : code to calculate the price of an European option using the Black-Scholes-Merton model. The code has three separate functions to calculate the price. The first uses the analytic formula, the second simulates the stock price only on the expiry date and finally the last function simulates the entire path of the stock price. 

3. <strong> zcb-term-structure </strong>: code to calculate and plot the term structure of interest rates from Zero Coupon Bond prices by simulating the evolution of the short rate lattice using a binomial tree.

                            
