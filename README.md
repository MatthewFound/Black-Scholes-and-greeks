# black-scholes-merton
Repository contains implementation of Black Scholes model and first-order Greeks for pricing European-style options. Here we combine the expressions involed in calculating 'call' and 'put' options using the Black Scholes model into a single object, massively streamlining the code provided in other repoisitories. We take this one step further by including update functionality such that the user can change model parameters dynamically without object reinitialisation. We also include a class for the calculation of first order Greeks. An an example of plottiing 3D visualisations of call price and put price for differnet model parameter combinations. 

The Black-Scholes model is a mathematical model for pricing European-style options. It gives a closed-form solution for the 'fair' price of an option, based on several key assumptions and variable e.g. constant volatility, no arbitrage, european style option, constant risk-free rate etc. The Greeks are measures of sensitivity of the price of a derivative instrument e.g. an option. They are essentially just partial derivatives with respect to the underlying model parameters. Inspecting the greeks allows us to manage and hedge risk associated with options. 



