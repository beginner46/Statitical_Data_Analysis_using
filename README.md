# Statitical_Data_Analysis_using_Julia

#Analysis of Nasdaq Closing Cross auctiondataset in Julia 

Each trading day on the Nasdaq Stock Exchange concludes with the Nasdaq
Closing Cross auction. This process establishes the official closing prices for
securities listed on the exchange. There are a lot of factors in this roughly 10
minutes auction that affect the closing price. Bid price which determines the
highest amount someone is willing to pay for the stock has a significant impact on
the closing price of the stock.

In this project the aim is to analyse the historic data for the daily ten minute closing
auction on the NASDAQ stock exchange. And finding the parameters having
maximum impact on bid_price using Julia. The data for this project was taken from
the following kaggle competition (https://www.kaggle.com/competitions/optivertrading-
at-the-close/data).

For better understanding of the heatmap and readability of the work it is recommended to open the pdf file, [Julia_codes.pdf](https://github.com/beginner46/Statitical_Data_Analysis_using_Julia)

Important libraries used - [CategoricalArrays](https://github.com/JuliaData/CategoricalArrays.jl), [StatsPlot](https://juliahub.com/ui/Packages/General/StatPlots/), [GLM](https://juliastats.org/GLM.jl/v0.11/)
