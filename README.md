# stock-graphing
Graphing stocks with Pandas and the TDAmeritrade API

I wanted to learn about public APIs, so this was the result of a few days of learning about them on my own time. I had to set up a TDAmeritrade brokerage
account to get access to the API, but it was free and it's pretty well-written. Getting the endpoints set up wasn't that difficult once I understood their
basic functions. 
I used Pandas to store the stock data mainly because it's very popular and I wanted to learn how it worked. The program queries TDAmeritrade for the
price history of the selected stock, and parses the returned JSON as a DataFrame. It then plots the share price against time, specifically for the year 2020 (thus far).
The parameters for the API query (period, frequency, etc) can also be changed, but some of the plotting code would be weird.
