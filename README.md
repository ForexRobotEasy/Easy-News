# Easy News Expert Advisor

This Expert Advisor is designed to place stop orders at a specified time based on news events. It can be used to trade breakouts for high rewards.

## Features

- Places buy and sell stop orders at a specified number of points from the current price.
- The stop orders are placed at a specified date and time of a news event.
- Automatically closes all open positions and pending orders upon deinitialization.

## Usage

1. Set the parameters for stop orders:
   - `stopOrderPoints`: The default number of points from the current price.
   - `newsEventTime`: The date and time of the news event.

2. Call the `PlaceStopOrder()` function in the `OnInit()` function to place the stop orders.
3. Call the `CloseAllOrders()` function in the `OnDeinit()` function to close all open positions and pending orders.

Please note that this code is a sample and not the official product. For detailed reviews and trading results of the official product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/easy-news-forex-software-review-trade-breakouts-for-high-rewards/). ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please use MQL5.

For more information and resources, please visit [forexroboteasy.com](https://forexroboteasy.com).

## Disclaimer

This code is provided as a sample and should be used for educational purposes only. ForexRobotEasy is not responsible for any losses incurred from the use of this code. Use at your own risk.
