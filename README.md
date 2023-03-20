# Pricing_Optimization
Executive Summary
The Price prediction model project should provide an algorithm to predict the next period prices that maximise the total firm’s profit, provided that accurate predictions of market conditions and of your per-unit cost in the next period are known.

Opportunity Statement


We are looking to hire developers to write a dynamic automated price optimization algorithm that can respond to market events and to competitors. The product we are asking you to price is available in different local markets and prices can be set each time period. You will be given historical data for a sample of markets: a history of prices, sales, and cost of sales for the firm whose prices you are trying to optimize, as well as an average of competitor prices and a variable summarizing market

Project Overview


To design and train the algorithm, using data from 55 markets. For each period (day) and market of the training data, observe the price of the firm you are asked to optimize for, their per-unit costs, their total units sold (normalized), their sales share in that period, an average of competitor prices, and a variable summarizing market conditions in that period (on a scale between 0 and 100). 




The Python code should have several clearly marked functions:

• process_training_data() - a function that takes the raw data and processes it to generate the inputs required to train the model.

• train_model() - a function that takes inputs and trains the model.

• predict_price() - a function that takes new inputs and the trained model as arguments, and recommends a new price for next period.

Any pricing algorithms companies implement can be subject to inspection and regulation by antitrust authorities, who are becoming increasingly concerned with algorithmic coordination. Examples of coordination include algorithms learning to "team up” with competitors and coordinate on maintaining high prices by punishing, or threatening to punish, competitor price reductions by reducing own price even further. 

Proposed Next Steps and Timeline

Further scope project and create charter outlining scope, metrics, etc. 

Train models with high accuracy to predict market prices
