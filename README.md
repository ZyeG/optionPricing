# optionPricing

## European option
### via black-scholes equation
### via MC simulations using geometric brownain motion for stock price, then compute discounted payoff as price; specifically,
- call payoff: max (S_t - K, 0)
- put payoff: max(K - S_t, 0), where S_t is stock price at maturity, K is strike price.
- discount to today: price = e^(-rT) * mean (payoffs)
