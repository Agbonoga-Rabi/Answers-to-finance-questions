# Answers-to-finance-questions
FINANCE
What is the Stock to Flow model?
The Stock to Flow (SF or S2F) model is a way to measure the abundance of a particular resource. The Stock to Flow ratio is the amount of a resource held in reserves divided by the amount it is produced annually.
The Stock to Flow model is generally applied to natural resources. Let’s take the example of gold. While the estimates may vary, the World Gold Council estimates that around 190,000 tons of gold have ever been mined. This amount (i.e., the total supply) is what we can refer to as the stock. Meanwhile, there are about 2,500-3,200 tons of gold mined each year. This amount is what we can refer to as the flow.
We can calculate the Stock to Flow ratio using these two metrics. But what does it actually mean? It essentially shows how much supply enters the market each year for a given resource relative to the total supply. The higher the Stock to Flow ratio, the less new supply enters the market relative to the total supply. As such, an asset with a higher Stock to Flow ratio should, in theory, retain its value well over the long-term.
In contrast, consumable goods and industrial commodities will typically have a low Stock to Flow ratio. Why is that? Since their value typically comes from them being destroyed or consumed, the inventories (the stock) are usually only there to cover demand. These resources don’t necessarily have high value as possessions, so they tend to work poorly as investment assets. In some exceptional cases, the price might rise quickly if there’s an anticipation of shortage in the future, but otherwise, production keeps up with demand.
It’s important to note that scarcity alone doesn’t necessarily mean that a resource should be valuable. Gold, for example, isn’t all that rare – after all, there are 190,000 tons available! The Stock to Flow ratio suggests that it’s valuable because annual production compared to the existing stock is relatively small and constant.
This model essentially treats bitcoins comparably to scarce commodities, like gold or silver.
Gold and silver are often called store of value resources. They, in theory, should retain their value over the long term due to their relative scarcity and low flow. What’s more, it is very difficult to significantly increase their supply within a short period of time.
According to the advocates of the Stock to Flow model, Bitcoin is a similar resource. It’s scarce, relatively costly to produce, and its maximum supply is capped at 21 million coins. Also, Bitcoin’s supply issuance is defined on the protocol level, which makes the flow completely predictable.
According to the proponents of this model, these properties combined create a scarce digital resource with profoundly compelling characteristics to retain value over the long-term. In addition, they assume that there’s a statistically significant relationship between Stock to Flow and market value. According to the model’s projections, Bitcoin’s price should see a significant increase over time due to it’s continually reduced Stock to Flow ratio.






The  Stock to Flow model is a bad model, this is because;
While Stock to Flow is an interesting model for measuring scarcity, it doesn’t account for all parts of the picture. Models are only as strong as their assumptions. For one thing, Stock to Flow relies on the assumption that scarcity, as measured by the model, should drive value. According to critics of Stock to Flow, this model fails if Bitcoin doesn’t have any other useful qualities other than supply scarcity.
Gold’s scarcity, predictable flow, and global liquidity have made it a relatively stable store of value compared to fiat currencies, which are prone to devaluation.
According to this model, Bitcoin’s volatility should also decrease over time. This is confirmed by historical data from Coinmetrics.The valuation of an asset requires taking into account its volatility. If the volatility is predictable to some extent, the valuation model may be more reliable. However, Bitcoin is notorious for its large price moves.While volatility might be decreasing on the macro level, Bitcoin has been priced in a free market from its inception. This means that the price is mostly self-regulated on the open market by users, traders, and speculators. Combine that with relatively low liquidity, and Bitcoin is likely to be more exposed to sudden spikes of volatility than other assets. So the model may not be able to account for this either.
Other external factors, such as economic Black Swan events, could also undermine this model. Though it’s worth noting that the same applies to essentially any model that tries to predict the price of an asset based on historical data. A Black Swan event, by definition, has an element of surprise. Historical data can’t account for unknown events.
Closing thoughts
The Stock to Flow model measures the relationship between the currently available stock of a resource and its production rate. It’s typically applied to precious metals and other commodities, but some argue it may be applicable to Bitcoin as well. 
In this sense, Bitcoin may be viewed as a scarce digital resource. According to this method of analysis, the unique propositions of Bitcoin should make it an asset that retains its value over the long-term. 
However, every model is as strong as its assumptions, and it may not be able to account for all aspects of Bitcoin valuation. What’s more, Bitcoin has only been around for a little more than ten years. Some might argue that long-term valuation models like the Stock to Flow need a larger data set for more reliable accuracy.

2) Stock price( P0)= $40, Exercise price(x)= $45, Volatility/ Standard deviation(SD)= 0.04, maturity time(t)= 4/12= 1/3, risk free rate=0.03
Using Black Scholes model;
Call price= Vc= PoNd1 -(X/e^krft)Nd2
d1= [ln (po/x) + (kRF +0.5sd^2)t]\sd√t
d2=[ln(po/x) + (kRF -0.5sd^2)t]\sd√t
Let's calculate for d1
d1= [ln(40/45) +(0.03+0.5(0.40)^2×1/3]\ 0.40√1/3
d1=[-0.117783 +(0.03+0.08)1/3]/ 0.40×0.57735
d1=[-0.117783+(0.11)1/3]/ 0.230999
d1=[-0.117783 +0.036666]\0.230999
d1=-0.081117/0.0230999
d1=-0.3512

d2= [ln(40/45) +(0.03-0.5×0.40^2)1/3]\0.40√1/3
d2=[-0.117783 +(0.03-0.08)1/3]\ 0.23093999
d2=[-0.117783-0.0166665]\0.23093999
d2=-0.1344495/0.23093999
d2=-0.5721
Using standard normal table;
Nd1=N(-0.3512)= 0.3632
Nd2= N(-0.5821) =0.2810

Then;
Call price= Vc=PoNd1- (X/e^kRft)Nd2
Vc= 40(0.3632) -[45/e^0.03×1/3]0.2810
Vc= 14.528-(45/1.010050] 0.2810
Vc=14.528- (44.55225)0.2810
Vc= $14.528 - $12.519
Vc=$2.009

