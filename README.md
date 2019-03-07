# Social-Cops-Data-Science-Intern-Challenge
## Aim: 
Your team is working on building a variety of insight packs to measure key trends in the Agriculture sector in India. You are presented with a data set around Agriculture and your aim is to understand trends in APMC (Agricultural produce market committee)/mandi price & quantity arrival data for different commodities in Maharashtra.

## Objective:
1) Test and filter outliers.
2) Understand price fluctuations accounting the seasonal effect
3) Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities
4) De-seasonalise prices for each commodity and APMC according to the detected seasonality type
5) Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised
6) Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.

## Variable description:
msprice- Minimum Support Price<br>
arrivals_in_qtl- Quantity arrival in market (in quintal)<br>
min_price- Minimum price charged per quintal<br>
max_price- Maximum price charged per quintal<br>
modal_price- Mode (Average) price charged per quintal

## Result:
The main reason for such a large price fluctuations between min. price set by the Government and actual price of the commodity can be: **Very high transportation cost**. Transportation Cost not only depends on the petrol/diesel prices but also depends on the geographical location of APMC. If the APMC is near to the farming lands, the cost is generally lower and very high in case of larger distances.
