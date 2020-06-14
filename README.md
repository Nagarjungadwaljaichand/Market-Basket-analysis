# Market-Basket-analysis
This is a simple example of Association analysis or market basket analysis

simple defination of market basket analysis is - If-Then scenario rules, for example, if item A is purchased then item B is likely to be purchased. 

Support, confidence and Lift defines the likelyhood of the associated products to be purchased or added to the basket/cart

Support is the relative frequency that the rules show up. In many instances, you may want to look for high support in order to make sure it is a useful relationship. However, there may be instances where a low support is useful if you are trying to find “hidden” relationships.

Confidence is a measure of the reliability of the rule. A confidence of .5 in the above example would mean that in 50% of the cases where Diaper and Gum were purchased, the purchase also included Beer and Chips. For product recommendation, a 50% confidence may be perfectly acceptable but in a medical situation, this level may not be high enough.

Lift is the ratio of the observed support to that expected if the two rules were independent (see wikipedia). The basic rule of thumb is that a lift value close to 1 means the rules were completely independent. Lift values > 1 are generally more “interesting” and could be indicative of a useful rule pattern.
[source: https://pbpython.com/market-basket-analysis.html]

you can find partical expamples of market basket analysis in Retail, Insurance, Telecommunications, Banks etc..

The specific data for this article comes from the UCI Machine Learning Repository and represents transactional data from 
a UK retailer from 2010-2011. This mostly represents sales to wholesalers so it is slightly different from consumer 
purchase patterns
