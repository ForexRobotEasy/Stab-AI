# Stab AI ReadMe File

## Introduction
This code implements a trading robot called Stab AI based on the assignment requirements mentioned in the terms of reference.

## Developer's Site
Forex Robot Easy is the developer of this trading robot. For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/stab-ai-review-safe-forex-trading-with-neural-network-optimization/). Note that Forex Robot Easy is not the official developer of this product. We only provide sample code that can work as described in this product.

## Required Libraries and Files
The following libraries and files are required for the proper functioning of Stab AI:
- Trade.mqh
- MA.mqh
- Stochastic.mqh
- NeuroBayes.mqh

## Global Variables
The code includes the following global variables:
- `MaximumSymbols`: Maximum number of trading symbols (default: 10)
- `InitialLotSize`: Initial lot size (default: 0.01)
- `MaximumOrders`: Maximum number of orders (default: 5)
- `DrawdownLevel`: Drawdown level (default: 0.2)
- `UseAutoLot`: Use autolot functionality (default: true)
- `MinLot`: Minimum lot size (default: 0.01)

## Trading Function
The code includes a trading function called `Trade()`. This function implements the following logic:
1. Checks if the maximum number of orders has been reached.
2. Checks if the maximum number of trading symbols has been reached.
3. Checks if the drawdown level has been reached.
4. Calculates the volume of the first order based on the autolot functionality or the minimum lot size.
5. Places a buy order using the calculated volume.
6. Increments the total number of orders if the order placement is successful.

## OnTick Function
The code includes an `OnTick()` function that calls the `Trade()` function on each tick.

For more information and detailed reviews of the Stab AI trading robot, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/stab-ai-review-safe-forex-trading-with-neural-network-optimization/).
